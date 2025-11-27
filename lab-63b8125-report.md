# AGNTCY: Building the Internet of Agents (IoA)

## Origins and Vision
AGNTCY was initiated by Outshift by Cisco in March 2025, with the goal of addressing the infrastructure gap preventing AI agents from collaborating at scale. It was launched on GitHub with contributions from Galileo and LangChain as core maintainers. By July 2025, AGNTCY was donated to the Linux Foundation, supported by major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

The vision of AGNTCY is to accelerate human work through agentic AI, enabling enterprises to create workflows and applications that combine internal and third-party agents for productivity gains. The mission is to build an open, interoperable IoA accessible to all, fostering innovation and collaboration.

## Core Capabilities
AGNTCY provides infrastructure for creating multi-agent applications through:
1. **Discovery**: Finding and evaluating the best agents for specific tasks.
2. **Composition**: Connecting agents into workflows across frameworks or vendors.
3. **Deployment**: Running multi-agent systems securely at scale.
4. **Evaluation**: Monitoring performance and improving efficiency.

## Technical Objectives
AGNTCY focuses on:
- **Interoperability**: Establishing protocols for efficient communication between agents from different vendors.
- **Security**: Ensuring secure interactions through authentication, authorization, and encryption.
- **Scalability**: Supporting a growing number of agents without compromising performance.
- **Standardization**: Developing consistent data models and schemas.

## Core Components
AGNTCY's architecture includes:
- **Open Agent Schema Framework (OASF)**: A data model for describing agents' attributes and ensuring unique identification.
- **Agent Directory**: A system for announcing and discovering agents or multi-agent applications.
- **Messaging SDK (SLIM)**: A protocol for secure and efficient communication between agents.
- **Identity Management**: Leveraging decentralized technologies for managing and verifying agent identities.
- **Observability and Evaluation**: Tools for monitoring and evaluating multi-agent applications.
- **Security**: Mechanisms to protect multi-agent applications.

## Identity Framework
AGNTCY provides a standardized framework for authenticating agents and validating metadata. It supports:
- **Open Identity Assignment**: No centralized authority required.
- **Collision-Free Identifiers**: Universally unique identifiers for agents.
- **Verifiable Credentials (VCs)**: Cryptographic validation of identities.

AGNTCY supports identity assignment through conventions (e.g., Identity Provider Accounts, Well-Known Identifiers) and standards (e.g., W3C Decentralized Identifiers).

## Benefits
AGNTCY offers:
- Enhanced collaboration between AI agents.
- Improved efficiency in developing AI-driven applications.
- Increased security for agent interactions.
- A future-proof architecture adaptable to advancements in AI technology.

## Reference Implementation
CoffeeAGNTCY serves as a reference implementation, demonstrating the core components for building multi-agent applications.

## References
1. [Identity in CoffeeAGNTCY](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)
2. [Introduction to AGNTCY](https://docs.agntcy.org/identity/identity/)
3. [AGNTCY Overview](https://docs.agntcy.org/)
4. [Identifiers in AGNTCY](https://docs.agntcy.org/identity/identifiers/)