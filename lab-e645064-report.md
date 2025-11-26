# AGNTCY: The Internet of Agents (IoA)

AGNTCY is an open-source initiative aimed at creating the Internet of Agents (IoA), a framework that enables AI agents to collaborate across organizational boundaries securely and efficiently. Below is a detailed overview of AGNTCY:

---

## Origins and Vision
AGNTCY was initiated by Outshift by Cisco in March 2025 to address the lack of infrastructure for AI agents to work together at scale. It was launched on GitHub with complete code, specifications, and services, and later donated to the Linux Foundation. Founding members include Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

The vision of AGNTCY is to accelerate human work through agentic workflows and applications, combining internal and third-party agents to leverage AI's full potential. The mission is to build an open, interoperable IoA accessible to all, fostering innovation and collaboration.

---

## Core Capabilities
AGNTCY provides infrastructure for multi-agent applications through:
1. **Discovery**: Finding and evaluating agents.
2. **Composition**: Connecting agents into workflows.
3. **Deployment**: Running systems at scale securely.
4. **Evaluation**: Monitoring and improving performance.

---

## Technical Objectives
- **Interoperability**: Common protocols for cross-platform communication.
- **Security**: Robust authentication and encryption mechanisms.
- **Scalability**: Cloud-native architecture for growing interactions.
- **Standardization**: Consistent data models and schemas.

---

## Key Components
1. **Open Agent Schema Framework (OASF)**: Extensible data model for describing agents' attributes.
2. **Agent Directory**: Inventory for announcing and discovering agents.
3. **Messaging SDK (SLIM)**: Secure communication protocol for agents.
4. **Identity**: Decentralized identity management for agents.
5. **Observability and Evaluation**: Tools for monitoring multi-agent applications.
6. **Security**: Mechanisms to protect applications.

---

## Identity Framework
AGNTCY emphasizes secure identity management for agents, MCP servers, and MASs. It supports:
- **Open Identity Assignment**: No centralized authority required.
- **Collision-Free Identifiers**: Universally unique IDs.
- **Verifiable Credentials (VCs)**: Cryptographic validation of identities.

---

## CoffeeAGNTCY Reference Implementation
CoffeeAGNTCY demonstrates AGNTCY's capabilities, including identity management and Tool-Based Access Control (TBAC). It uses Ory Hydra as its identity provider and showcases workflows for agent authentication and secure collaboration.

---

## Benefits
- Enhanced collaboration between AI agents.
- Improved efficiency in developing AI-driven applications.
- Increased security for interactions.
- Future-proof architecture adaptable to AI advancements.

---

## References
1. [Introduction to AGNTCY](https://docs.agntcy.org/identity/identity/)
2. [AGNTCY Overview](https://docs.agntcy.org/)
3. [Identifiers in AGNTCY](https://docs.agntcy.org/identity/identifiers/)
4. [Identity in CoffeeAGNTCY](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)