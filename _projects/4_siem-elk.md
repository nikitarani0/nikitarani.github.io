---
layout: page
title: Custom SIEM Implementation
description: Centralized threat detection with the ELK Stack, mapped to MITRE ATT&CK
img: assets/img/siem_cover.png
importance: 4
category: work
github: https://github.com/nikitarani0/custom-siem-elk-stack
---

A centralized threat detection system ingesting security logs from Windows and
Linux endpoints in real time, with detection logic mapped directly to the
MITRE ATT&CK framework for structured, defensible alerting.

**Stack:** Elasticsearch, Logstash, Kibana, Winlogbeat, Filebeat, MITRE ATT&CK

**Key capabilities:**
- Real-time log ingestion from Windows and Linux endpoints via Winlogbeat and Filebeat
- Logstash parsing pipelines normalizing and correlating events across log sources
- 15+ detection rules targeting brute-force attacks, privilege escalation, and
  suspicious SSH activity, mapped to MITRE ATT&CK techniques
- Automated threshold-based alerting, reducing mean time to detect active threats
- Kibana dashboard visualizing failed login trends, SSH geolocation anomalies,
  and top alert categories for stakeholder reporting
- Signal validation against contextual log data to eliminate false positives,
  with documented investigation and remediation workflows aligned to the
  incident response lifecycle
