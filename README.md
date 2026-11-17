<div align="right">
  <a href="README.pt-BR.md">🇧🇷 Leia em Português</a>
</div>

# Networking & Security → DevSecOps Roadmap — João Pedro Ribeiro

**Brazilian Army Sergeant → Network Infrastructure & Security | DevSecOps (in progress) | Brazil**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaop-net)
[![GitHub](https://img.shields.io/badge/GitHub-joaop-net-181717?style=flat-square&logo=github)](https://github.com/joaop-net)

---

## About

I've been serving in the Brazilian Army for 8 years. I enlisted in 2018, took part in the Federal Intervention in Rio de Janeiro, and graduated from the Sergeants' School of Arms (ESA) in 2022. Today I'm a career Third Sergeant working in vehicle maintenance — and I'm building my move into network infrastructure through the Army's technical training and daily, documented study.

In parallel, I'm completing a Computer Networks degree at Estácio University. I did technical internships in Linux and Networking at the Centro de Telemática de Área (5º CTA, Brazilian Army), and I'm currently enrolled in Network Fundamentals, Data Cabling, and IT Logistics courses at the Centro de Telemática de Área (1º CTA). In 2025 I earned my first certification (Oracle OCI Foundations).

My focus is **network infrastructure**: how networks are addressed, switched, routed, secured, and kept running. Switches, routers, cabling, addressing plans, connectivity troubleshooting — the physical and logical layers that everything else sits on. This is the career I'm building, not a step toward something else: you can't operate or secure infrastructure you don't understand. I'm currently preparing for the **CCNA 200-301 v2.0** (exam window Apr–May 2027): baseline diagnostic done on Nov 7, 2026, and a week-by-week plan in place — fundamentals first, then switching, routing and services.

Every phase here ends the same way: something built, documented, and explained — because in infrastructure, an undocumented fix is a fix nobody can repeat.

---

## Roadmap Progress

The route runs **depth-first through network infrastructure and security**, then infrastructure operations, with network automation on top.

| Phase | Topic | Focus | Status |
|:-----:|-------|-------|:------:|
| 01 | Networking Fundamentals | CCNA 1 (ITN) — OSI/TCP-IP, IPv4 & IPv6 addressing, subnetting, switching, static routing, ICMP | 🔄 In progress |
| 02 | Switching, Routing & Wireless | CCNA 2 (SRWE) — VLANs, trunking, inter-VLAN routing, STP, EtherChannel, WLANs, dynamic routing | ⏳ Next |
| 03 | Enterprise Networking & Security | CCNA 3 (ENSA) — ACLs, NAT, WAN, VPN, network security, QoS, monitoring, automation intro | ⏳ Planned |
| 04 | Linux + Network Security | Server administration, hardening, firewalling, SSH, logging | ⏳ Planned |
| 05 | Infrastructure & Operations | Virtualization, monitoring and alerting, backup & restore, incident investigation | ⏳ Planned |
| 06 | Advanced Routing & Automation | OSPF in depth, IPv6, BGP basics, network automation with Python | ⏳ Planned |

---

## Repository Structure

```
network-engineering-journey/
├── check-ins/                            # Daily study logs (bilingual EN/PT)
├── fase-01-redes-fundamentos/            # CCNA 1 — ITN
│   ├── labs/               # Numbered labs: mechanism + real-world bridge
│   ├── conceitos/          # Atomic notes (1 concept per file) with flashcards
│   ├── resumos/            # Weekly phase summaries
│   └── projeto-integrador/ # End-of-phase practical project
├── fase-02-redes-avancado/               # CCNA 2 — SRWE
├── fase-03-redes-empresariais-seguranca/ # CCNA 3 — ENSA
├── fase-04-linux-seguranca/              # Linux + network security
├── fase-05-infra-operacoes/              # Virtualization, monitoring, backup
└── fase-06-roteamento-avancado-automacao/ # OSPF, IPv6, BGP, Python automation
```

Each phase follows the same layout:
- `labs/` — numbered labs (objective, mechanism, examples, real-world bridge)
- `conceitos/` — atomic concept notes with flashcards (`Question?::Answer`)
- `resumos/` — weekly summaries exported from Obsidian
- `projeto-integrador/` — end-of-phase practical project

---

## Stack

### Currently Using

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Next on the roadmap

OSPF · IPv6 · BGP basics · network automation with Python

---

## Certifications

| Certification | Status |
|---|:---:|
| Oracle Cloud Infrastructure Foundations Associate | ✅ May 2025 |
| Introduction to Cybersecurity — Cisco Networking Academy (via EsCom, Brazilian Army) | ✅ Mar 2026 |
| Computer Networks — Centro de Telemática de Área, 5º CTA (Brazilian Army) | ✅ Apr 2026 |
| Linux — Centro de Telemática de Área, 5º CTA (Brazilian Army) | ✅ Apr 2026 |
| Network Fundamentals (Teltec partnership) — Centro de Telemática de Área, 1º CTA (Brazilian Army) | 🎯 In progress 2026 |
| Network & Data Cabling — Centro de Telemática de Área, 1º CTA (Brazilian Army) | 🎯 In progress 2026 |
| IT Logistics for Supported Units — Centro de Telemática de Área, 1º CTA (Brazilian Army) | 🎯 In progress 2026 |
| CCNA 1: Introduction to Networks — Cisco Networking Academy (via EsCom, Brazilian Army) | 🎯 In progress 2026 |
| CCNA 2: Switching, Routing & Wireless Essentials — Cisco Networking Academy (via EsCom) | ⏳ Next |
| CCNA 3: Enterprise Networking, Security & Automation — Cisco Networking Academy (via EsCom) | ⏳ Planned |
| CCNA 200-301 (v2.0) — Cisco Certified Network Associate | 🎯 Main target — exam window Apr–May 2027 (v2.0 blueprint) |

---

## Current Goals

- Build real depth in **network infrastructure** — addressing, switching, routing, connectivity, security
- Complete the full Cisco academy track (**CCNA 1 → 2 → 3**) via the Army Communications School (EsCom)
- Turn every phase into something hands-on: topologies, diagrams, and documented configurations
- Get sharper at **network troubleshooting** — reading the symptom before touching the config
- Practice **explaining technical work in English**, since documentation and communication are half the job
- Grow into **DevSecOps** — automation and security built on top of that foundation, not instead of it

---

## Earlier Exploratory Projects

Before starting this structured roadmap, I explored several DevOps topics on my own. These repositories contain early hands-on experiments — imperfect, but real.

| Repository | Description |
|---|---|
| [learning-terraform](https://github.com/joaop-net/learning-terraform) | First experiments with Terraform and AWS S3 provisioning |
| [CI-CD](https://github.com/joaop-net/CI-CD) | Early CI/CD pipeline experiment with Terraform, Docker, and GitHub Actions |
| [github-actions-simples](https://github.com/joaop-net/github-actions-simples) | First GitHub Actions CI pipeline with Python and pytest |
| [first-image-docker](https://github.com/joaop-net/first-image-docker) | My first Docker image — Nginx serving a static HTML page |
| [github-access-audit](https://github.com/joaop-net/github-access-audit) | Shell script for GitHub access auditing, built while studying Bash |

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaop-net)
[![GitHub](https://img.shields.io/badge/GitHub-joaop-net-181717?style=flat-square&logo=github)](https://github.com/joaop-net)
