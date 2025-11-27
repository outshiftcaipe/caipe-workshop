### Detailed Working Example of an MVP Setup for a Loki Agent with an MCP Server

#### Step 1: Setting Up the Loki Agent and MCP Server
1. **Clone the Template Repository**:
   - Use the Petstore/Template Agent as a starting point for creating new agents.
   - Clone the repository:
     ```bash
     git clone https://github.com/cnoe-io/ai-platform-engineering.git
     cd ai-platform-engineering/agents/template
     ```

2. **Start the MCP Server**:
   - Use the built-in mock server for testing:
     ```bash
     docker run -d -p 8080:8080 swaggerapi/petstore3
     ```

3. **Configure the Environment**:
   - Create a `.env` file with the following configuration:
     ```env
     # Agent Configuration
     AGENT_NAME=petstore_agent
     LLM_PROVIDER=azure-openai

     # Petstore API Configuration
     PETSTORE_API_URL=http://localhost:8080
     PETSTORE_API_KEY=test-key

     # A2A Configuration
     A2A_AGENT_HOST=localhost
     A2A_AGENT_PORT=8000

     # MCP Configuration
     MCP_HOST=localhost
     MCP_PORT=9000
     ```

4. **Run the MCP Server**:
   - Start the MCP server in stdio mode:
     ```bash
     make run-a2a
     ```

5. **Test the Setup**:
   - Test basic operations using `curl`:
     ```bash
     curl -X GET "http://localhost:8080/api/v3/pet/findByStatus?status=available"
     curl -X GET "http://localhost:8080/api/v3/pet/1"
     ```

#### Step 2: Query Examples Using Loki Query Language
1. **Basic Log Query**:
   - Retrieve logs from a specific application:
     ```loki
     {app="my-application"} |= "error"
     ```

2. **Filter by Time Range**:
   - Query logs within a specific time range:
     ```loki
     {app="my-application"} | logfmt | duration > 5s
     ```

3. **Aggregate Logs**:
   - Count the number of logs per application:
     ```loki
     count_over_time({app="my-application"}[5m])
     ```

4. **Advanced Query with Template Functions**:
   - Use template functions to format the output:
     ```loki
     {app="my-application"} | line_format "{{.timestamp}} - {{.message}}"
     ```

#### Step 3: Guide the Agent's Prompt Using Loki Query Language Documentation
- Refer to the following Loki Query Language documentation for detailed guidance:
  - [Query Reference](https://github.com/grafana/loki/blob/main/docs/sources/query/query_reference.md)
  - [Query Examples](https://github.com/grafana/loki/blob/main/docs/sources/query/query_examples.md)
  - [Template Functions](https://github.com/grafana/loki/blob/main/docs/sources/query/template_functions.md)

#### Example Use Cases
1. **Log Analysis**:
   - "Find all error logs from the last 24 hours."
   - Query:
     ```loki
     {level="error"} | json | duration > 24h
     ```

2. **Performance Monitoring**:
   - "Show the average response time for the last 7 days."
   - Query:
     ```loki
     avg_over_time({app="web-server"}[7d])
     ```

3. **Alert Management**:
   - "Create an alert for when CPU usage exceeds 80%."
   - Query:
     ```loki
     {app="web-server"} | json | cpu > 80
     ```

#### References
1. [Petstore/Template Agent Documentation](https://cnoe-io.github.io/ai-platform-engineering/agents/template)
2. [Loki Query Reference](https://github.com/grafana/loki/blob/main/docs/sources/query/query_reference.md)
3. [Loki Query Examples](https://github.com/grafana/loki/blob/main/docs/sources/query/query_examples.md)
4. [Loki Template Functions](https://github.com/grafana/loki/blob/main/docs/sources/query/template_functions.md)