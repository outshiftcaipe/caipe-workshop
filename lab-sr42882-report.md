# AGNTCY: Building the Internet of Agents

## Origins
AGNTCY was initiated by Outshift by Cisco, with the vision of an Internet of Agents to address the lack of collaboration among isolated AI agents. The project officially launched in March 2025 on GitHub, with contributions from Galileo and LangChain as core maintainers. By July 2025, AGNTCY was donated to the Linux Foundation, supported by major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

## Vision
AGNTCY aims to accelerate human work by enabling enterprises to create workflows and applications that combine internal and third-party agents. The goal is to leverage AI for significant productivity gains and innovation.

## Mission
AGNTCY is committed to building accessible, open-source infrastructure for the Internet of Agents. It fosters a diverse, collaborative space for developing software components and services that address challenges in agentic workflows and multi-agent applications.

## Capabilities
AGNTCY simplifies the creation of multi-agent applications through:
- **Discover**: Identifying the best agents for specific tasks.
- **Compose**: Connecting agents into workflows across frameworks and vendors.
- **Deploy**: Running multi-agent systems securely at scale.
- **Evaluate**: Monitoring and improving performance over time.

## Technical Objectives
AGNTCY focuses on:
- **Interoperability**: Establishing protocols for efficient communication among agents from different platforms.
- **Security**: Ensuring secure interactions through authentication, authorization, and encryption.
- **Scalability**: Designing cloud-native architecture for growing agent interactions.
- **Standardization**: Developing consistent data models and schemas.

## Core Components
AGNTCY's architecture includes:
1. **Open Agent Schema Framework (OASF)**: Extensible data models for describing agents' attributes.
2. **Agent Directory**: A system for announcing and discovering agents using OASF.
3. **Messaging SDK (SLIM)**: Protocols for secure, low-latency communication between agents.
4. **Identity**: Decentralized technologies for managing and verifying agent identities.
5. **Observability and Evaluation**: Tools for monitoring multi-agent applications.
6. **Security**: Mechanisms to protect multi-agent systems.

## Benefits
AGNTCY offers:
- Enhanced collaboration among AI agents.
- Improved efficiency in developing AI-driven applications.
- Increased security for agent interactions.
- A future-proof architecture adaptable to advancements in AI.

## Identity Management
AGNTCY provides a standardized framework for authenticating agents and validating metadata. It supports decentralized identity management using conventions like Identity Provider Accounts and standards like W3C Decentralized Identifiers (DIDs). This ensures secure and trustworthy interactions among agents, MCP servers, and MASs.

## CoffeeAGNTCY
CoffeeAGNTCY is a reference implementation demonstrating AGNTCY's core components. It uses Ory Hydra as its identity provider and showcases Tool-Based Access Control (TBAC) for secure communication and task execution among agents.

## References
- [AGNTCY Documentation](https://docs.agntcy.org/)