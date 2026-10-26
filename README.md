# Awesome-Internet-Of-Things-IOT

## Top Internet of Things (IoT) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Device Connectivity, Telemetry Ingestion & IoT Application Enablement*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Internet of Things (IoT)**. These tools enable organizations to connect and manage devices at scale, ingest and process telemetry data, build real-time dashboards, and automate workflows across industrial, consumer, and smart infrastructure deployments.



**Examples** include ServiceNow Internet of Things, AWS IoT Core, Microsoft Azure IoT Hub, Google Cloud IoT, PTC ThingWorx, Software AG Cumulocity IoT, Particle, Samsara, Siemens MindSphere, and Cisco IoT Control Center (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted IoT platforms, MQTT brokers, and device management frameworks—ideal for organizations building sovereign IoT infrastructure without per-device or per-message licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Internet of Things](https://www.servicenow.com/)**  

  Enterprise IoT integration on the Now Platform for connecting operational technology and smart devices to IT workflows; enables event-driven automation, CMDB enrichment with OT asset data, and incident creation from device telemetry.



- **[AWS IoT Core](https://aws.amazon.com/iot-core/)**  

  Managed cloud service for connecting IoT devices to AWS; supports MQTT, HTTPS, and WebSocket protocols, device shadows, rules engine for routing messages to AWS services, and integration with Lambda, S3, and DynamoDB.



- **[Microsoft Azure IoT Hub](https://azure.microsoft.com/en-us/products/iot-hub)**  

  Cloud gateway for device connectivity and management; provides bidirectional communication, per-device authentication, device twins, direct methods, and integration with Azure Stream Analytics, Functions, and Machine Learning.



- **[Google Cloud IoT](https://cloud.google.com/solutions/iot)**  

  Google Cloud's IoT solution suite (now primarily via partners and Pub/Sub-based architectures) for device telemetry ingestion, processing with Dataflow, and integration with BigQuery and AI/ML services.



- **[PTC ThingWorx](https://www.ptc.com/en/products/thingworx)**  

  Industrial IoT platform with rapid application development, augmented reality integration, and device connectivity for manufacturing and industrial use cases.



- **[Software AG Cumulocity IoT](https://www.softwareag.com/)**  

  IoT application enablement platform with device management, real-time analytics, and low-code app building for telecom, manufacturing, and smart city deployments.



- **[Particle](https://www.particle.io/)**  

  IoT platform combining hardware (cellular/WiFi modules), device management, and cloud connectivity for connected product developers.



- **[Samsara](https://www.samsara.com/)**  

  Connected operations platform for fleet, equipment, and site visibility; combines IoT hardware with cloud software for transportation, logistics, and industrial operations.



- **[Siemens MindSphere](https://www.siemens.com/)**  

  Industrial IoT operating system for connecting products, plants, and systems to enable data-driven services and digital twin capabilities.



- **[Cisco IoT Control Center](https://www.cisco.com/)**  

  IoT device connectivity management platform for cellular IoT deployments; provides SIM lifecycle management, connectivity analytics, and automated operations for large-scale device fleets.



## Open-Source GitHub Projects



- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  

  The most widely adopted open-source IoT platform (Apache 2.0 Community Edition, 21k+ GitHub stars); covers device management, telemetry collection, data processing via rule chains, dashboards, and alarm management in a single platform; natively supports MQTT, HTTP, and CoAP; stores time-series data in PostgreSQL or Cassandra; Docker-first setup reaches a live dashboard in 60–90 minutes; Pro edition adds clustering, multi-tenancy, and white-labeling .



- **[Magistrala](https://github.com/absmach/magistrala)**  

  Linux Foundation-recognized open-source IoT platform (Apache 2.0) built as microservices in Go; focuses on clean primitives—messaging, identity, secure device connectivity—that you assemble into a platform; containerized with Docker and orchestrated with Kubernetes; suited for teams that want to build their own IoT stack from focused components rather than adopt an opinionated all-in-one solution .



- **[dgiot](https://github.com/dgiot/dgiot)**  

  Open-source industrial IoT aggregation engine (Erlang/OTP, 12k+ GitHub stars) built for million-device scale; supports 300+ protocols including Modbus and OPC UA; features device shadow with gen_statem, ontology engine, rule engine, and TDengine time-series storage; one-click Docker deployment completes in ~6 minutes .



- **[MapexOS](https://github.com/Mapex-Solutions/mapexOS)**  

  Open-source enterprise IoT platform for multi-tenant operations across HTTP, MQTT, and LoRaWAN; features telemetry ingestion with authenticated HTTP/MQTT, JavaScript-based per-asset data transformation pipelines, dynamic event routing, a DAG workflow engine inspired by Temporal.io, plugin UI for workflow nodes, and RBAC with organization hierarchies; self-hostable via Docker Compose with multi-arch images for Linux, Apple Silicon, and Raspberry Pi .



- **[EMQX](https://github.com/emqx/emqx)**  

  Open-source distributed MQTT broker (Apache 2.0 community edition) designed for million-device-scale messaging; supports MQTT 5.0, clustering, rule engine, multi-tenancy, and a connector ecosystem; the messaging layer for high-scale IoT deployments, typically paired with ThingsBoard or a custom dashboard on top .



- **[EsoCore](https://github.com/newmatik/EsoCore)**  

  Full-stack open-source industrial IoT platform for factory machinery monitoring; spans PCB hardware designs, STM32 embedded firmware, Django REST API backend, and a Nuxt.js user portal; supports Modbus RTU over RS-485 and other industrial fieldbus protocols; ideal for teams building custom condition-monitoring or predictive maintenance systems .



- **[Mongoose OS](https://github.com/cesanta/mongoose-os)**  

  Open-source IoT firmware development framework (Apache 2.0 Community Edition) for microcontrollers including ESP32, ESP8266, STM32, and CC3220; features OTA firmware updates with rollback, flash encryption, mbedTLS security, and built-in integration for AWS IoT, Google IoT Core, Azure, and generic MQTT servers; code in C or JavaScript .



- **[NAOS](https://github.com/256dpi/naos)**  

  Open-source collection of protocols, libraries, and tools for building interactive smart devices on ESP32 microcontrollers (Apache 2.0); provides configuration parameters, multi-dimensional metrics, file-system access, remote firmware updates, device provisioning, password protection, and live log tailing; connectivity over WiFi, Ethernet, BLE, MQTT, HTTP/WS, Serial, and OSC; includes CLI, TUI explorer, and SDKs for Go, TypeScript, and Swift .



- **[DeviceSDK](https://github.com/device-sdk/devicesdk)**  

  Free, self-hosted IoT platform (AGPL-3.0) for writing TypeScript device scripts and running the server on your own hardware (Raspberry Pi, NUC, NAS, Docker); connects ESP32 and Raspberry Pi Pico microcontrollers over WebSocket; single-container deployment with SQLite persistence, mDNS auto-discovery, and a CLI for login, project init, deploy, and log tailing .



- **[nodrix](https://github.com/decoded-cipher/nodrix)**  

  Open-source single-tenant IoT platform designed to deploy entirely into your own Cloudflare account (Workers, Durable Objects, D1, R2); telemetry over HTTPS or WebSocket with auto-created variables, real-time drag-and-drop dashboards, two-way device control, visual automations, and a native MCP server for AI client integration .



### Additional Strong Open-Source Options



- **Node-RED** — Visual flow-based programming tool with extensive IoT nodes for MQTT, HTTP, and industrial protocols; commonly paired with ThingsBoard or EMQX for rapid integration and automation prototyping .

- **Eclipse Mosquitto** — Lightweight open-source MQTT broker suitable for smaller deployments or edge gateways; a simpler alternative to EMQX when million-device scale is not required.

- **Grafana + InfluxDB/TDengine** — Open-source visualization and time-series storage stack; frequently combined with Magistrala or EMQX for custom IoT dashboards and analytics.



**Frameworks for building custom systems**: Combine **ThingsBoard** for an all-in-one IoT platform with device management and rule chains, **EMQX** for high-scale MQTT messaging, **Magistrala** for microservices-based custom platform assembly, and **dgiot** for industrial protocol-heavy deployments in a self-hosted IoT stack; layer **Node-RED** for visual integration workflows and **Grafana** for advanced visualization.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IoT platforms handling device telemetry and operational data must comply with applicable security and privacy regulations; device authentication and encrypted communication are essential for production deployments.

- Self-hosted open-source solutions vary significantly in scope—ThingsBoard provides a complete all-in-one platform, while Magistrala and EMQX focus on specific layers requiring assembly; industrial deployments with legacy protocols may benefit from dgiot's protocol breadth.

- Verify license terms for commercial use; ThingsBoard, Magistrala, EMQX, Mongoose OS, and NAOS use Apache 2.0, dgiot is open-source, and DeviceSDK uses AGPL-3.0 .



---



**Made for IoT engineers, platform architects, industrial operations teams, and connected product developers.**  

Let's make IoT infrastructure more open, scalable, and device-sovereign.
