# AGNTCY Report

## Origins
AGNTCY was initiated by Outshift by Cisco in March 2025, with the goal of addressing the infrastructure gap preventing AI agents from collaborating across organizational boundaries. It was launched on GitHub with complete code, specifications, and services, and later donated to the Linux Foundation in July 2025. Founding members include Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

## Vision
AGNTCY envisions accelerating human work through agentic AI workflows and applications. It aims to enable enterprises to combine internal and third-party agents to leverage AI's full potential, driving innovation and productivity.

## Mission
The mission is to build an accessible Internet of Agents through open-source collaboration. AGNTCY focuses on developing software components and services to solve challenges in agentic workflows and multi-agent applications.

## Capabilities
AGNTCY simplifies the creation of multi-agent applications through:
1. **Discover**: Identifying the best agents for tasks.
2. **Compose**: Connecting agents into workflows across frameworks or vendors.
3. **Deploy**: Running multi-agent systems securely at scale.
4. **Evaluate**: Monitoring and improving performance over time.

## Technical Objectives
1. **Interoperability**: Establishing protocols for efficient communication between agents from different vendors.
2. **Security**: Ensuring secure interactions through authentication, authorization, and encryption.
3. **Scalability**: Designing architectures to support growing numbers of agents and interactions.
4. **Standardization**: Developing standardized data models for consistent data representation.

## Core Components
1. **Open Agent Schema Framework (OASF)**: Extensible data model for describing agents' attributes and ensuring unique identification.
2. **Agent Directory**: Enables discovery of agents or multi-agent applications described using OASF.
3. **Messaging SDK (SLIM)**: Protocol for secure and efficient communication between AI agents.
4. **Identity**: Decentralized system for managing and verifying agent identities.
5. **Observability and Evaluation**: Tools for monitoring and evaluating multi-agent applications.
6. **Security**: Mechanisms to protect multi-agent applications.

## Identity Management
AGNTCY provides a standardized framework for authenticating agents and validating metadata. It supports decentralized identifiers (DIDs) and verifiable credentials (VCs) for cryptographic validation. Identity assignment is open, collision-free, and verifiable, ensuring secure interactions within the IoA ecosystem.

## CoffeeAGNTCY
CoffeeAGNTCY is a reference implementation demonstrating AGNTCY's core components. It uses Ory Hydra as its identity provider and showcases Tool-Based Access Control (TBAC) for secure communication and collaboration between agents.

## Benefits
1. **Enhanced Collaboration**: Facilitates seamless communication and data exchange between AI agents.
2. **Improved Efficiency**: Reduces complexity in integrating diverse AI agents.
3. **Increased Security**: Protects sensitive data and prevents unauthorized access.
4. **Future-Proof Architecture**: Scalable and adaptable to advancements in AI technology.

## References
1. [AGNTCY Overview](https://docs.agntcy.org/)
2. [Identity in AGNTCY](https://docs.agntcy.org/identity/identity/)
3. [CoffeeAGNTCY Identity](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)
4. [Records in AGNTCY](https://docs.agntcy.org/dir/ads-records/)