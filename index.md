---

layout: col-sidebar
title: OWASP Honeypot
tags: owasp honeypot
level: 2
type: documentation

---

# OWASP Honeypot-Project

The goal of the OWASP Honeypot Project is to identify emerging attacks against web applications and report them to the community, in order to facilitate protection against such targeted attacks.

Based around the earlier OWASP/WASC Distributed Web Honeypots Project (https://github.com/SpiderLabs/owasp-distributed-web-honeypots)

The primary aims of the project are

*    Real-time, detailed Web Application Threat Attack Data
*    Threat Reports to the community

## Organization of the repository

This repository is organized into various directories. Below table shows the purpose of each one. 

| Directory | Purpose | 
| --- | --- | 
| `honeytraps` | Focuses on building honeytraps and reporting threat intelligence | 
| `mds_elk` | Shows a PoC for sending the ModSecurity Audit Logs to ELK using Filebeat|
| `misp-doc` | Assists in setting the MISP Server and creating threat events using PyMISP |
| `mlogc_elk` | Shows a PoC for sending the ModSecurity Audit Logs to ELK using ModSecurity Audit Log Collector (mlogc) |

Please go to respective directories for complete documentation.

# Project Roadmap

We keep the project roadmap as [issues in the repo](https://github.com/OWASP/Honeypot-Project/issues)
