# Awesome-Remote-Device-Monitoring

## Top Remote Device Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on IoT Device Management, Telemetry Collection, Dashboards, Fleet Monitoring, Edge Connectivity & Remote Diagnostics*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Remote Device Monitoring**. These systems collect telemetry from connected devices, provide real-time dashboards, enable remote configuration and diagnostics, and support fleet-scale IoT operations across industrial, consumer, and embedded use cases.



**Examples** include Datacake, Blynk, Ubidots, Losant, ThingsBoard, Particle Console, EMQX Cloud, ClearBlade, MachineMetrics, and Memfault (the category leaders).



**Open-source emphasis**: This domain has a particularly strong open-source ecosystem. **ThingsBoard** is the leading full-featured open-source IoT platform, complemented by **Node-RED**, **EdgeX Foundry**, **OpenRemote**, **EMQX**, **Eclipse Ditto**, and related tools. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ThingsBoard Cloud / Professional](https://thingsboard.io/)**  

  Full-featured IoT platform (also available open-source) offering device management, rule engine, dashboards, and multi-tenancy for remote monitoring at scale.



- **[Datacake](https://datacake.co/)**  

  Low-code IoT platform popular for LPWAN and industrial device monitoring with white-label options, dashboards, and easy integrations.



- **[Blynk](https://blynk.io/)**  

  Hardware-agnostic IoT platform with mobile apps, device connectivity, and remote control/monitoring capabilities for makers and commercial products.



- **[Ubidots](https://ubidots.com/)**  

  Industrial IoT platform focused on condition monitoring, data visualization, alerts, and application building for remote assets.



- **[Losant](https://www.losant.com/)**  

  Enterprise IoT application enablement platform with edge computing, workflows, and remote device management features.



- **[Particle Console](https://www.particle.io/)**  

  Device cloud and management console for Particle hardware and connected products, covering provisioning, monitoring, and over-the-air updates.



- **[EMQX Cloud](https://www.emqx.com/)**  

  Managed MQTT broker and IoT messaging platform with monitoring, rule engines, and integration capabilities for large device fleets.



- **[ClearBlade, MachineMetrics, Memfault](https://www.clearblade.com/)**  

  Specialized platforms for edge intelligence, industrial machine monitoring, and embedded device observability / crash reporting.



- **[Other remote device monitoring platforms](https://thingsboard.io/)**  

  Additional commercial solutions covering SCADA-style monitoring, predictive maintenance, and fleet diagnostics.



## Open-Source GitHub Projects



- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  

  Leading open-source IoT platform for device management, data collection, processing, visualization, and rule-based automation. Supports MQTT, HTTP, CoAP, LwM2M and offers both Community and Professional editions.



- **[ThingsBoard IoT Gateway](https://github.com/thingsboard/thingsboard-gateway)**  

  Open-source gateway that integrates legacy and third-party protocols (Modbus, OPC-UA, BACnet, BLE, etc.) with the ThingsBoard platform.



- **[Node-RED](https://github.com/node-red/node-red)**  

  Flow-based, low-code programming tool widely used for IoT integrations, data transformation, and connecting devices to dashboards or cloud services.



- **[EdgeX Foundry](https://github.com/edgexfoundry)**  

  Open-source, vendor-neutral edge computing framework for industrial IoT, providing device services, data processing, and southbound/northbound connectivity.



- **[OpenRemote](https://github.com/openremote/openremote)**  

  Full-stack open-source IoT platform with strong support for asset management, automation rules, dashboards, and multi-tenancy—particularly suited to smart buildings and energy use cases.



- **[EMQX](https://github.com/emqx/emqx)**  

  High-performance open-source MQTT broker capable of scaling to millions of concurrent device connections, with rule engines and data integration features.



- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  

  Open-source digital-twin framework that provides a consistent API and state management layer for IoT devices and assets.



- **[Other IoT platforms & tools](https://github.com/search?q=IoT+platform+OR+device+management+open+source)**  

  Additional projects including Magistrala (formerly Mainflux), Kaa, ChirpStack (LoRaWAN), and various MQTT/dashboard combinations.



### Additional Strong Open-Source Options



- **Visualization**: Grafana for unified dashboards on top of IoT time-series data.

- **Time-series databases**: InfluxDB, TimescaleDB, or Cassandra used with the platforms above.

- **Protocol brokers & adapters**: Mosquitto, additional MQTT/CoAP/LwM2M implementations.

- **Edge agents & gateways**: Community gateways for Modbus, OPC-UA, and industrial protocols.

- **Firmware & OTA**: Open tools for remote firmware updates and device provisioning.

- **Observability for embedded**: Projects focused on crash reporting, metrics, and logging from constrained devices (complementary to Memfault-style solutions).



**Frameworks for building custom systems**:  

The strongest open-source foundation is **ThingsBoard** (full platform) combined with **Node-RED** for flexible integrations, **EMQX** or Mosquitto for messaging, and **Grafana** for advanced visualization.  

For industrial edge scenarios, add **EdgeX Foundry**; for digital twins, add **Eclipse Ditto**; for smart-building focus, consider **OpenRemote**.  

Commercial platforms (Datacake, Blynk, Ubidots, Losant, Particle, ClearBlade, MachineMetrics, Memfault, etc.) provide managed hosting, polished mobile experiences, specialized vertical features, and lower operational overhead.  

Many teams run fully self-hosted ThingsBoard + supporting open-source components for data control and cost efficiency, while others use managed cloud offerings for faster time-to-value.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Remote device monitoring systems collect operational and sometimes sensitive telemetry. Security (authentication, encryption, access control), data privacy, and reliable connectivity are critical.

- Open-source IoT platforms offer transparency and freedom from per-device licensing but require expertise in deployment, scaling, hardening, and ongoing maintenance. Evaluate total cost of ownership, security posture, and support needs carefully.



---



**Made for IoT engineers, embedded developers, industrial operators, product teams, and platform architects.**  

Let's make remote device monitoring open, scalable, and interoperable—whether through managed services or fully self-hosted open-source stacks.
