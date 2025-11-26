# AGNTCY Report

## Overview
AGNTCY is an open-source initiative aimed at creating an interoperable "Internet of Agents" (IoA) to enable collaboration among AI agents across organizational boundaries. Below is a detailed overview of AGNTCY:

### Origins and Vision
AGNTCY was initiated by Outshift by Cisco in March 2025 to address the lack of infrastructure for AI agents to collaborate at scale. It was launched on GitHub with contributions from Galileo and LangChain as core maintainers. By July 2025, AGNTCY was donated to the Linux Foundation, with major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat as formative members.

The vision of AGNTCY is to accelerate human work by enabling enterprises to create workflows and applications that combine internal and third-party agents. The goal is to foster innovation and productivity through an open, interoperable IoA.

### Mission
AGNTCY's mission is to build a diverse, collaborative space for developing software components and services that solve key problems in agentic workflows and multi-agent applications. It aims to make the IoA accessible to all.

## Capabilities
AGNTCY provides infrastructure for creating multi-agent applications through:
1. **Discover**: Finding and evaluating the best agents for tasks.
2. **Compose**: Connecting agents into workflows across frameworks or vendors.
3. **Deploy**: Running multi-agent systems securely at scale.
4. **Evaluate**: Monitoring performance and improving efficiency.

## Technical Objectives
AGNTCY focuses on:
- **Interoperability**: Establishing protocols for efficient communication among agents.
- **Security**: Ensuring secure interactions through authentication and encryption.
- **Scalability**: Supporting a growing number of agents and interactions.
- **Standardization**: Developing consistent data models and schemas.

## Core Components
AGNTCY's architecture includes:
1. **Open Agent Schema Framework (OASF)**: A data model for describing agents' attributes.
2. **Agent Directory**: A system for discovering agents and multi-agent applications.
3. **Messaging SDK (SLIM)**: A protocol for secure and efficient communication between agents.
4. **Identity**: A decentralized system for managing and verifying agent identities.
5. **Observability and Evaluation**: Tools for monitoring multi-agent applications.
6. **Security**: Mechanisms to protect multi-agent applications.

## Identity Management
AGNTCY provides a standardized framework for authenticating agents and validating metadata. It supports:
- **Open Identity Assignment**: No centralized authority is required.
- **Collision-Free Identifiers**: Universally unique IDs for agents.
- **Verifiable Credentials (VCs)**: Cryptographic validation of IDs and provenance.

AGNTCY supports identity assignment through conventions (e.g., Identity Provider Accounts, Well-Known Identifiers) and standards (e.g., W3C Decentralized Identifiers).

## Benefits
AGNTCY offers:
- Enhanced collaboration among AI agents.
- Improved efficiency in developing AI-driven applications.
- Increased security for interactions between agents.
- A future-proof architecture adaptable to advancements in AI technology.

## Reference Implementation
CoffeeAGNTCY is a reference implementation demonstrating AGNTCY's core components for building multi-agent applications.

## References
1. [Identity in CoffeeAGNTCY - Agntcy](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)
2. [Agntcy Overview](https://docs.agntcy.org/)
3. [Identifiers - Agntcy](https://docs.agntcy.org/identity/identifiers/)
4. [Introduction - Agntcy](https://docs.agntcy.org/identity/identity/)
