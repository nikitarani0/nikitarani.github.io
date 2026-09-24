---
layout: page
title: INCOPs
description: Secure DevSecOps Pipeline — end-to-end CI/CD with integrated security scanning
img: assets/img/incops_cover.png
importance: 2
category: work
github: https://github.com/nikitarani0/incops
---

An end-to-end CI/CD pipeline with security controls built in at every stage rather
than bolted on afterward.

**Stack:** Jenkins, GitHub Actions, CodeQL, Trivy, OWASP ZAP, Prometheus, Grafana

**Key capabilities:**
- SAST via CodeQL, container scanning via Trivy, DAST via OWASP ZAP
- Automated Kubernetes deployment gated on scan results
- Prometheus + Grafana observability for pipeline health and security metrics
