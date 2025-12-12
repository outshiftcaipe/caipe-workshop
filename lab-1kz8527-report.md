# AGNTCY: A Comprehensive Overview

## Introduction
AGNTCY is an open-source initiative aimed at creating the Internet of Agents (IoA), a collaborative ecosystem where AI agents can interact seamlessly across organizational boundaries. It was launched by Outshift by Cisco in March 2025 and later donated to the Linux Foundation, with contributions from major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

The project addresses the infrastructure gap that prevents AI agents from collaborating effectively, focusing on discovery, identity, messaging, and observability components.

---

## Vision and Mission

### Vision
AGNTCY envisions an interoperable Internet of Agents that accelerates human work by enabling enterprises to create workflows combining internal and third-party agents. This approach aims to maximize productivity and innovation across industries.

### Mission
The mission of AGNTCY is to build an open-source, community-driven infrastructure for IoA. It fosters collaboration to innovate, develop, and maintain software components that solve key challenges in agentic workflows and multi-agent applications.

---

## Origins
AGNTCY originated from Outshift by Cisco's vision of an Internet of Agents. The foundational white paper identified the need for infrastructure to enable collaboration among AI agents. By July 2025, over 75 companies had joined the effort, leading to its donation to the Linux Foundation.

---

## Core Capabilities
AGNTCY simplifies the creation of multi-agent applications through the following steps:
1. **Discover**: Find and evaluate the best agents for specific tasks.
2. **Compose**: Connect agents into workflows across frameworks and vendors.
3. **Deploy**: Run multi-agent systems securely at scale.
4. **Evaluate**: Monitor performance and improve efficiency over time.

---

## Technical Objectives
AGNTCY focuses on:
- **Interoperability**: Establishing protocols for efficient communication between agents.
- **Security**: Ensuring secure interactions through authentication and encryption.
- **Scalability**: Supporting a growing number of agents without compromising performance.
- **Standardization**: Developing consistent data models and schemas.

---

## Core Components
### Open Agent Schema Framework (OASF)
An extensible data model for describing agents' attributes and ensuring unique identification.

### Agent Directory
Allows organizations to announce and discover agents or multi-agent applications.

### Messaging SDK
SLIM (Secure Low-latency Interactive Messaging) protocol ensures secure and efficient communication between agents.

### Identity
A decentralized system for managing and verifying agent identities.

### Observability and Evaluation
Telemetry tools for monitoring multi-agent applications.

### Security
Tools to protect multi-agent applications.

---

## Identity Management
AGNTCY provides a standardized framework for authenticating agents and validating metadata. Key features include:
- **Open**: No centralized authority required for assigning identities.
- **Collision-free**: Universally unique identifiers for entities.
- **Verifiable**: Backed by Verifiable Credentials (VCs).

### Assignment Approaches
1. **Conventions**: Identity Provider Accounts (e.g., Okta, Microsoft AD) and well-known identifiers (e.g., Google's A2A protocol).
2. **Standards**: W3C Decentralized Identifiers (DIDs) and Verifiable Credentials.

---

## CoffeeAGNTCY: A Reference Implementation
CoffeeAGNTCY demonstrates the core components of AGNTCY, showcasing how multi-agent applications can be built using its infrastructure.

---

## Benefits
1. **Enhanced Collaboration**: Seamless communication fosters sophisticated solutions.
2. **Improved Efficiency**: Standardized protocols reduce integration complexity.
3. **Increased Security**: Robust mechanisms protect sensitive data.
4. **Future-Proof Architecture**: Scalable design adapts to advancements in AI.

---

## Conclusion
AGNTCY is a transformative initiative that aims to create an open, interoperable Internet of Agents. By addressing key challenges in agentic workflows, it paves the way for accelerated innovation and productivity across industries.

---

## References
1. [Identity in CoffeeAGNTCY](https://docs.agntcy.org/coffee-agntcy/identity-coffee-agntcy/)
2. [AGNTCY Overview](https://docs.agntcy.org/)
3. [Identifiers in AGNTCY](https://docs.agntcy.org/identity/identifiers/)
4. [Introduction to AGNTCY Identity](https://docs.agntcy.org/identity/identity/)