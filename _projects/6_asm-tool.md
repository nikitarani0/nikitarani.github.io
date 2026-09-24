---
layout: page
title: ASM Tool
description: Attack Surface Mapper — offensive recon automation
img: assets/img/asm_cover.png
importance: 6
category: work
github: https://github.com/nikitarani0/asm-tool
---

An offensive security reconnaissance automation tool that chains together
industry-standard recon utilities into a single attack-surface mapping workflow.
**In progress.**

**Stack:** Python, subfinder, amass, httpx, nmap, nuclei

**Key capabilities:**
- Automated subdomain enumeration (subfinder + amass) and live-host probing (httpx)
- Port/service scanning via nmap, vulnerability scanning via nuclei
- Consolidated output for fast attack-surface triage
