# AGNTCY Report

## Origins
AGNTCY was initiated by Outshift by Cisco in March 2025 to address the lack of collaboration among isolated AI agents. It was launched on GitHub with complete code, specifications, and services, supported by Galileo and LangChain as core maintainers. By July 2025, AGNTCY was donated to the Linux Foundation, with Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat as formative members.

## Vision and Mission
- **Vision**: AGNTCY aims to accelerate human work by enabling enterprises to create workflows and applications combining internal and third-party agents. It envisions an open, interoperable IoA to foster innovation and maximize value across industries.
- **Mission**: AGNTCY is committed to building accessible infrastructure for IoA, fostering collaboration to innovate and maintain software components for agentic workflows and multi-agent applications.

## Capabilities
AGNTCY simplifies the creation of multi-agent applications through:
1. **Discover**: Identifying the best agents for specific tasks.
2. **Compose**: Connecting agents into workflows across frameworks or vendors.
3. **Deploy**: Running multi-agent systems securely at scale.
4. **Evaluate**: Monitoring and improving performance over time.

## Technical Objectives
1. **Interoperability**: Establishing protocols for efficient communication among AI agents from different vendors.
2. **Security**: Ensuring secure interactions through authentication, authorization, and encryption.
3. **Scalability**: Designing cloud-native architecture to support growing agent interactions.
4. **Standardization**: Developing standardized data models for consistent data representation.

## Core Components
1. **Open Agent Schema Framework (OASF)**: Extensible data model for describing agents' attributes and ensuring unique identification.
2. **Agent Directory**: Enables discovery of agents or multi-agent applications described using OASF.
3. **Messaging SDK (SLIM)**: Protocol for secure and efficient communication between AI agents.
4. **Identity**: Decentralized system for managing and verifying agent identities.
5. **Observability and Evaluation**: Tools for monitoring multi-agent applications.
6. **Security**: Mechanisms to protect multi-agent applications.

## Identity Management Framework
AGNTCY provides a standardized framework for authenticating agents and validating metadata. Key features include:
- **Open and Collision-Free**: No centralized authority required; each entity has a unique identifier.
- **Verifiable Credentials (VCs)**: Used for authenticating IDs and provenance.
- **Identity Assignment Approaches**:
  - **Conventions**: Identity Provider Accounts (e.g., Okta, Microsoft AD) and well-known identifiers (e.g., Google's Agent2Agent protocol).
  - **Standards**: W3C Decentralized Identifiers (DIDs) and associated standards for decentralized identity management.

## CoffeeAGNTCY Implementation
CoffeeAGNTCY is a reference implementation demonstrating AGNTCY's core components. It uses Ory Hydra as its identity provider and showcases Tool-Based Access Control (TBAC) for secure communication and collaboration among agents.

## Benefits
1. **Enhanced Collaboration**: Seamless communication fosters sophisticated solutions.
2. **Improved Efficiency**: Standardized protocols simplify integration and deployment.
3. **Increased Security**: Robust mechanisms protect sensitive data.
4. **Future-Proof Architecture**: Scalable design adapts to advancements in AI.

For more detailed information, you can explore the [AGNTCY documentation](https://docs.agntcy.org/).

## References
- [AGNTCY Overview](https://docs.agntcy.org/)
- [Identity Management in AGNTCY](https://docs.agntcy.org/identity/identity/)
- [CoffeeAGNTCY Identity Implementation](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)