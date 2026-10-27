# Awesome-Autonomous-Threat-Management

# Awesome-Autonomous-Threat-Management

Copy-Item README.md README.md.bak -Force
# Manual step: replace SaaS and Open-Source sections with content above
git add README.md
git commit -m "docs: add autonomous threat management pricing (Darktrace €21-52K/year per 1000 devices, CrowdStrike $7.99-19.99/device, SentinelOne $179.99-229.99/endpoint, Vectra $40/IP, Cybereason $150-1300K/year) and open-source XCLOAK; flag ServiceNow/Cortex XSIAM gaps"
git push
# Awesome-Autonomous-Threat-Management

# Top Autonomous Threat Management
**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Autonomous Threat Detection, XDR, EDR, AI-Driven Security Operations & Automated Response*

**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Threat Management**. These solutions use behavioral analytics, machine learning, and automation to detect, investigate, and respond to threats across endpoints, networks, and cloud environments with minimal human intervention.

**Examples** include ServiceNow Autonomous Threat Management, Darktrace, CrowdStrike Falcon, SentinelOne, Vectra AI, Palo Alto Networks Cortex, Cybereason, Cynet, Trellix, and Sophos (the category leaders).

**Open-source emphasis**: Fully autonomous commercial XDR/EDR platforms dominate enterprise adoption, but strong open-source building blocks exist. **Wazuh**, **Velociraptor**, **Security Onion**, **TheHive + Cortex**, **OSSEC**, **Falco**, and related projects enable powerful self-hosted detection, hunting, and response capabilities. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[ServiceNow Autonomous Threat Management](https://www.servicenow.com/)**  
  ServiceNow’s security operations capabilities that combine threat intelligence, automation, and workflow orchestration for autonomous or semi-autonomous threat response.

- **[Darktrace](https://www.darktrace.com/)**  
  AI-powered cyber defense platform using self-learning AI to detect and autonomously respond to novel threats across enterprise environments.

- **[CrowdStrike Falcon](https://www.crowdstrike.com/)**  
  Leading cloud-native endpoint protection and XDR platform known for lightweight agents, threat intelligence, and rapid detection and response.

- **[SentinelOne](https://www.sentinelone.com/)**  
  Autonomous endpoint protection platform that combines AI-driven prevention, detection, and automated remediation across endpoints and cloud workloads.

- **[Vectra AI](https://www.vectra.ai/)**  
  AI-driven network detection and response (NDR) platform focused on identifying attacker behaviors across hybrid and multi-cloud environments.

- **[Palo Alto Networks Cortex](https://www.paloaltonetworks.com/cortex)**  
  Integrated XDR and security operations platform that correlates data across endpoints, networks, and cloud for automated threat detection and response.

- **[Cybereason](https://www.cybereason.com/)**  
  Defense platform focused on detecting and disrupting multi-stage attacks with behavioral analytics and automated response capabilities.

- **[Cynet](https://www.cynet.com/)**  
  All-in-one autonomous security platform combining endpoint, network, and user protection with built-in automation and managed detection options.

- **[Trellix](https://www.trellix.com/)**  
  Enterprise security platform (formed from McAfee Enterprise and FireEye) offering XDR, endpoint, and threat intelligence capabilities.

- **[Sophos](https://www.sophos.com/)**  
  Cybersecurity platform providing endpoint protection, XDR, and managed detection and response with strong automation features.

## Open-Source GitHub Projects
- **[Wazuh](https://github.com/wazuh/wazuh)**  
  Leading open-source XDR and SIEM platform. Provides endpoint agents, threat detection, file integrity monitoring, vulnerability detection, and active response capabilities.

- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  
  Powerful open-source endpoint visibility and hunting platform. Uses VQL (Velociraptor Query Language) for live digital forensics, threat hunting, and incident response at scale.

- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)**  
  Free and open-source platform for threat hunting, enterprise security monitoring, and log management. Integrates Suricata, Zeek, Wazuh, Elastic Stack, and more.

- **[TheHive](https://github.com/TheHive-Project/TheHive)**  
  Open-source scalable Security Incident Response Platform designed to make life easier for SOCs, CSIRTs, and CERTs. Works tightly with Cortex for automated analysis.

- **[Cortex](https://github.com/TheHive-Project/Cortex)**  
  Open-source observable analysis and active response engine. Extends TheHive with analyzers and responders for automated threat intelligence and containment actions.

- **[OSSEC](https://github.com/ossec/ossec-hids)**  
  Classic open-source Host-based Intrusion Detection System (HIDS) that performs log analysis, file integrity checking, policy monitoring, and active response.

- **[Falco](https://github.com/falcosecurity/falco)**  
  Cloud-native runtime security tool (CNCF project) that detects anomalous behavior in applications and containers using system call monitoring.

- **[OpenEDR](https://github.com/ComodoSecurity/openedr)**  
  Open-source Endpoint Detection and Response project providing telemetry collection and detection capabilities, particularly focused on Windows environments.

- **[MISP](https://github.com/MISP/MISP)**  
  Open-source threat intelligence platform for sharing, storing, and correlating Indicators of Compromise (IOCs) and threat information.

- **[Suricata](https://github.com/OISF/suricata)** + **[Zeek](https://github.com/zeek/zeek)**  
  High-performance open-source network threat detection engines. Suricata focuses on IDS/IPS signatures and Zeek on network analysis and behavioral visibility.

### Additional Strong Open-Source Options
- Endpoint / XDR-style platforms: **Wazuh**, **Velociraptor**, **OpenEDR**.
- Full monitoring stacks: **Security Onion**.
- Incident response & automation: **TheHive** + **Cortex**.
- Network detection: **Suricata**, **Zeek**.
- Runtime / container security: **Falco**.
- Threat intelligence: **MISP**.
- Accepting that commercial autonomous platforms (CrowdStrike, SentinelOne, Darktrace, Palo Alto Cortex, Vectra, Cynet) still lead in fully managed AI-driven prevention, automated remediation at scale, threat intelligence feeds, and enterprise support.

**Frameworks for building custom systems**:  
Deploy **Wazuh** agents for endpoint visibility and active response → use **Velociraptor** for deep hunting and forensics → centralize with **Security Onion** or Elastic/OpenSearch → orchestrate investigations with **TheHive + Cortex** → enrich with **MISP**. Ideal for security teams that need data sovereignty, customization, and the ability to build transparent detection and response pipelines.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Threat detection and response involve critical security decisions. Open-source tools provide transparency and control but require skilled operators for tuning, maintenance, and incident handling. Commercial platforms often include managed services and advanced AI models that may reduce operational burden. This list is not security, compliance, or incident response advice. Always test thoroughly in your environment.

---
**Made for security engineers, SOC teams, blue teamers, and open-source advocates.**

Let's keep threat detection and response powerful, transparent, and under your control.
