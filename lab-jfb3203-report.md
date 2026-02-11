# AGNTCY: Building the Internet of Agents

## Overview
AGNTCY is an open-source initiative aimed at creating an interoperable Internet of Agents (IoA). It provides the foundational infrastructure for AI agents to collaborate securely and efficiently across organizational boundaries. AGNTCY's mission is to accelerate innovation and productivity by enabling seamless agentic workflows and multi-agent applications.

## Origins
AGNTCY was conceptualized by Outshift, a division of Cisco, to address the challenges of isolated AI agents. In March 2025, AGNTCY was launched on GitHub with complete code, specifications, and services. By July 2025, it was donated to the Linux Foundation, supported by major companies like Cisco, Dell Technologies, Google Cloud, Oracle, and Red Hat.

## Vision and Mission
- **Vision**: To accelerate human work by enabling agentic workflows and applications that combine internal and third-party agents.
- **Mission**: To build an open, collaborative space for developing software components and services that solve key problems in agentic workflows and multi-agent applications.

## Key Components
### 1. **SLIM (Secure Low-latency Interactive Messaging)**
SLIM is a protocol that ensures secure and efficient communication between AI agents. It supports various messaging patterns, including request-reply, unicast, publisher/subscriber, and group communication. SLIM integrates with OpenTelemetry for observability and provides SDKs for developers.

### 2. **Identity Service**
The AGNTCY Identity Service manages and verifies digital identities for Agentic Services. It supports decentralized identity management using W3C standards like Decentralized Identifiers (DIDs) and Verifiable Credentials (VCs). Key features include:
- Verifying existing identities.
- Registering new Agentic Services.
- Implementing Task-Based Access Control (TBAC).

### 3. **Agent Directory**
The Agent Directory allows organizations to announce and discover agents or multi-agent applications. It supports A2A agent cards and MCP server descriptions, forming an inventory for the Internet of Agents.

### 4. **Observability and Security**
AGNTCY provides tools for telemetry collection, evaluation, and security to ensure trust and protection in multi-agent applications.

## Use Cases
### 1. **CoffeeAGNTCY**
A reference implementation demonstrating SLIM's capabilities in multi-agent workflows. It uses SLIM for group communication and NATS for publisher/subscriber patterns.

### 2. **Telemetry Integration**
SLIM is used to build custom OpenTelemetry Collectors for telemetry data collection and analysis.

### 3. **Agent-to-Agent Communication**
Facilitates secure and efficient communication between agents in a multi-agent application.

## Benefits
- Enhanced collaboration between agents across organizational boundaries.
- Improved observability and evaluation of multi-agent applications.
- Secure and trustworthy interactions through decentralized identity verification.

## Resources
- [AGNTCY Documentation](https://docs.agntcy.org/)
- [SLIM Documentation](https://docs.agntcy.org/slim/)
- [OpenTelemetry over SLIM](https://docs.agntcy.org/slim/slim-otel/)

---
This report provides a comprehensive overview of AGNTCY, its components, and its applications. For further details, refer to the provided resources.

[Current date: 2026-02-11, Current date/time: 2026-02-11 12:11:26]