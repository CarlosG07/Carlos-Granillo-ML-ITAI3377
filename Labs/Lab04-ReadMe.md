# IIoT Sensor Network Simulation

## Overview
This project demonstrates a simulated Industrial Internet of Things (IIoT) sensor network. The goal is to explore how devices communicate using common IIoT protocols and to analyze their performance, efficiency, and real-world applications.

The system focuses on lightweight communication between devices and simulates data transmission using modern IIoT messaging standards.

## Objectives
- Understand how IIoT devices communicate in a network
- Compare popular IIoT protocols:
  - MQTT (Message Queuing Telemetry Transport)
  - CoAP (Constrained Application Protocol)
  - OPC UA (Open Platform Communications Unified Architecture)
- Simulate message exchange between devices
- Evaluate protocol performance, efficiency, and use cases

## System Description
The project simulates a network of sensors and devices communicating through different protocols.

### Key Components:
- Sensor Nodes (simulated devices)
- Communication Protocol Layer (MQTT, CoAP, OPC UA)
- Message Broker / Server
- Data Transmission & Testing Environment

## Technologies Used
- Python (for simulation and testing)
- MQTT libraries (e.g., paho-mqtt)
- CoAP frameworks
- OPC UA tools
- Networking concepts and simulation tools

## Protocol Comparison

| Protocol | Communication Model | Strengths | Limitations |
|----------|-------------------|----------|------------|
| MQTT | Publish/Subscribe | Lightweight, efficient, low bandwidth | Requires broker |
| CoAP | Request/Response | Low overhead, REST-like | Limited features |
| OPC UA | Client/Server & Pub/Sub | Secure, scalable, industrial-grade | Complex |

## Simulation & Testing
- Simulated publishing and subscribing using MQTT
- Tested communication reliability and latency
- Compared protocol behavior under different conditions

## Key Findings
- MQTT is ideal for low-power, bandwidth-constrained environments
- CoAP works well for simple device-to-device communication
- OPC UA provides strong security and structure for industrial systems

## Challenges
- Differentiating between MQTT and CoAP due to similar lightweight design
- Understanding OPC UA complexity and layered architecture

### Solutions:
- Conducted hands-on simulations
- Broke complex topics into smaller parts
- Used practical examples to reinforce learning

## Future Improvements
- Integrate real sensors instead of simulations
- Build a live dashboard for data visualization
- Implement edge computing features
- Expand security testing

## Learning Outcomes
- Gained hands-on experience with IIoT communication protocols
- Improved understanding of system design and networking
- Learned how to choose protocols based on system requirements
