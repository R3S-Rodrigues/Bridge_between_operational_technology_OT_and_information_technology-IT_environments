Bridge: Operational Technology (OT) & Information Technology (IT) Convergence

Overview
This repository contains the documentation and reference architecture for an end-to-end IIoT (Industrial Internet of Things) solution. The central objective is to convert raw data from field sensors into business intelligence assets, ensuring cybersecurity and data governance in compliance with global standards.
System Architecture
The solution is divided into four main processing layers:

![Diagrama IIoT de sensores cromatograficos](docs\Diagrama IIoT de sensores cromatograficos.jpg)

1. Shop Floor Layer (OT)
Acquisition: Data capture via Chromatographic Sensors (FID/TCD) and other industrial devices.
Digitisation: Signal conditioning, filtering and A/D (Analogue-Digital) conversion to ensure reading integrity.
Field Protocols: Data encapsulation in Modbus TCP/IP standard for deterministic communication.
2. Connectivity & Edge Layer
Edge Computing: Edge processing via an IIoT Gateway to reduce latency and filter data.
Interoperability: Translation of protocols to IT standards such as OPC-UA and MQTT.
Physical Security: Implementation of Industrial Firewalls for network segmentation between factory and office.



3. Cloud & Governance Layer (IT)
Secure Transport: Data transmission via MQTTS with authentication based on Digital Certificates (X.509).
Big Data & Analytics: Integration into Data Lake and Data Warehouse following ISO 27001.
Compliance: Structure developed under LGPD/GDPR guidelines.
4. Operational Efficiency & Export
Visualisation: Advanced dashboards for monitoring KPIs (OEE, availability, predictive maintenance).
Corporate Integration: Data export via APIs to ERP, MES and analytical spreadsheet systems.
📂 Repository Structure
docs/: Architecture diagrams and technical white papers.
edge/: Scripts for local processing and protocol translation.
cloud/: Cloud infrastructure and security configurations.
analytics/: Data models and notebooks for predictive analytics.
dashboards/: Templates for BI tools.
Pillars of Value
Throughout the entire flow, the project supports continuous benefits of Customisation, Process Configuration, Auditing (Traceability) and Operational Efficiency.
How to use this project
To understand the technical implementation, start by exploring the detailed diagram in the docs/ folder and the X.509 security configuration guides.

Author: [https://github.com/R3S-Rodrigues] Licence: MIT
 
