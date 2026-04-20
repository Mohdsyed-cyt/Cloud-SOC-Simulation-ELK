# Cloud SOC Simulation & IoT Threat Monitoring

## Project Overview
This repository documents the architecture and deployment of a cloud-based Security Operations Center (SOC) environment. The project leverages **AWS**, **Docker**, and the **ELK Stack (Elasticsearch, Logstash, Kibana)** to ingest, process, and visualize time-series data and security alerts from IoT endpoints. 

## Technical Execution & Architecture
* **Cloud Infrastructure:** Provisioned and managed AWS EC2 instances, utilizing **AWS CloudWatch** to establish baseline metrics and trigger automated alarms during simulated stress events (CPU Floods).
* **Containerized Logging Pipeline:** Orchestrated a scalable telemetry pipeline using **Docker** and **Filebeat** to securely forward endpoint logs to the centralized SIEM.
* **Threat Detection (IDS):** Deployed **Suricata** and engineered custom intrusion detection rules to actively identify malicious IoT traffic, specifically targeting MQTT rate-limiting (flood attacks) and malformed JSON payloads.
* **SIEM & Visualization:** Configured **Logstash** for data parsing and built interactive **Kibana** dashboards to provide real-time visibility into ingestion health, event counts, and critical security anomaly spikes.

## Methodology & Tools
* **Infrastructure:** AWS (EC2, CloudWatch), Linux (Ubuntu), Docker.
* **SIEM / Logging:** ELK Stack (Elasticsearch, Logstash, Kibana), Filebeat.
* **Network Security:** Suricata IDS, Custom Rule Engineering, MQTT Protocol Analysis.

## Professional Certifications Applied
* **CompTIA Security+**
* **ISC2 Certified in Cybersecurity (CC)**

---
**View the Full Architecture & Analysis Report:** [Download PDF Here](./Mohdsyed_Cloud_SOC_Simulation_Report.pdf)
EOF
