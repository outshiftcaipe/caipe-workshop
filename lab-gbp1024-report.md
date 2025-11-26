# AGNTCY Report

## Overview
AGNTCY is an initiative focused on creating an open, interoperable Internet of Agents (IoA). It aims to enable AI agents to collaborate across organizational boundaries, addressing the infrastructure gap that prevents agents from working together at scale.

### Origins and Vision
- **Origins**: AGNTCY was initiated by Outshift by Cisco, recognizing the need for collaboration among AI agents. It launched in March 2025 with contributions from Galileo and LangChain, and by July 2025, it was donated to the Linux Foundation with major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat as members.
- **Vision**: AGNTCY envisions accelerating human work through agentic workflows and applications, combining internal and third-party agents to leverage AI's power for productivity gains.

### Mission and Capabilities
- **Mission**: AGNTCY is an open-source collective committed to building the IoA accessible to all, fostering innovation and collaboration in agentic workflows and multi-agent applications.
- **Capabilities**: It provides tools for discovering, composing, deploying, and evaluating multi-agent systems, ensuring interoperability, security, scalability, and standardization.

## Technical Objectives and Components
- **Objectives**: AGNTCY focuses on interoperability, security, scalability, and standardization to enable efficient communication and collaboration among AI agents.
- **Core Components**:
  - **Open Agent Schema Framework (OASF)**: Describes agents' attributes and ensures unique identification.
  - **Agent Directory**: Facilitates the discovery of agents and multi-agent applications.
  - **Messaging SDK (SLIM)**: Defines secure and efficient communication standards.
  - **Identity System**: Manages and verifies agent identities using decentralized technologies.
  - **Observability and Evaluation Tools**: Enable monitoring and improvement of multi-agent applications.

## Identity Framework
AGNTCY provides a standardized framework for authenticating agents and validating metadata. It supports decentralized identity management using W3C standards like Decentralized Identifiers (DIDs) and Verifiable Credentials (VCs). The identity system ensures secure and trustworthy interactions among agents, MCP servers, and MASs.

## CoffeeAGNTCY
CoffeeAGNTCY is a reference implementation demonstrating AGNTCY's core components. It uses Ory Hydra as its identity provider and showcases Tool-Based Access Control (TBAC) for secure communication and collaboration among agents.

## References
1. [Introduction - AGNTCY](https://docs.agntcy.org/identity/identity/)
2. [AGNTCY Overview](https://docs.agntcy.org/)
3. [Identifiers - AGNTCY](https://docs.agntcy.org/identity/identifiers/)
4. [Identity in CoffeeAGNTCY - AGNTCY](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)
5. [AGNTCY Documentation Repository](https://github.com/agntcy/docs)
6. [CoffeeAGNTCY Repository](https://github.com/agntcy/coffeeAgntcy)
7. [AGNTCY Identity Repository](https://github.com/agntcy/identity)
8. [AGNTCY Governance Repository](https://github.com/agntcy/governance)