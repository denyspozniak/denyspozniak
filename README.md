# Hi there, I'm Denys Pozniak 👋

![VoIP](https://img.shields.io/badge/VoIP-1A6FB5?style=for-the-badge)
![Voice AI](https://img.shields.io/badge/Voice%20AI-7B3FE4?style=for-the-badge)
![SIP](https://img.shields.io/badge/SIP-0A7E8C?style=for-the-badge)
![DevOps](https://img.shields.io/badge/DevOps-2F855A?style=for-the-badge)

[![Kamailio Handbook](https://img.shields.io/badge/Kamailio%20Handbook-1A6FB5?style=for-the-badge&logo=gitbook&logoColor=white)](https://denyspozniak.github.io/kamailio-handbook/)
[![SEMS Handbook](https://img.shields.io/badge/SEMS%20Handbook-C2410C?style=for-the-badge&logo=gitbook&logoColor=white)](https://denyspozniak.github.io/sems-handbook/)
[![OpenSIPS Hover](https://img.shields.io/open-vsx/dt/denyspozniak/opensips-hover?style=for-the-badge&label=OpenSIPS%20Hover&color=007ACC&logo=visualstudiocode&logoColor=white)](https://open-vsx.org/extension/denyspozniak/opensips-hover)

## 🚀 VoIP Architect | Voice AI Engineer | DevOps

I've been immersed in the IT industry since 2005, beginning my journey with FreeBSD administration. From there, I transitioned into working extensively with Cisco networking equipment, which paved the way for my eventual move into VoIP. My diverse experience has equipped me with a comprehensive understanding of solution architecture.

Today, I identify myself as a **VoIPOps Architect** — a unique blend of DevOps and VoIP, symbolizing my expertise in both domains. My current focus is bringing AI into voice: integrating LLM-driven agents and speech services into real SIP infrastructure.

---

## 🎓 Certifications

- 🔷 **Cisco CCVP/CCNP/CCDP** (CSCO11178125)
- 📡 **Iskratel SI3000**

---

## 🛠️ Tech Stack

### ☎️ VoIP Technologies
```
Kamailio | OpenSIPS | FreeSWITCH | Asterisk | RTPengine | SEMS | Homer
```

### 🌐 Networking
```
Cisco | Mikrotik
```

### 📡 Protocols
```
SIP | SIP-I/T | SS7 | H323 | OSPF | BGP
```

### ⚙️ DevOps & Infrastructure
```
Kubernetes | Docker | Terraform | Ansible | ArgoCD
```

---

## 🧭 Where My Expertise Runs — End to End

- **Interconnect** — SS7 / SIP-I / SIP-T, carrier peering, number routing
- **Signalling** — Kamailio, OpenSIPS: registration, dispatching, failover, DMQ replication, anycast balancing
- **Media** — RTPengine, SEMS, FreeSWITCH: transcoding, recording, RTP/RTCP statistics, one-way-audio forensics
- **Session border** — SBC design, topology hiding, NAT traversal, TLS/SRTP
- **Platform** — Kubernetes, Docker, Terraform, Ansible, ArgoCD; CI/CD for stateful telecom workloads
- **Operations** — Homer, per-call capture, latency and quality troubleshooting at scale
- **Voice AI** — LLM-driven voice agents on top of real SIP infrastructure

Twenty years across the stack: from a FreeBSD box in 2005 to Cisco networks,
then carrier VoIP, and now cloud-native voice platforms with AI in the loop.

---

## ✍️ Selected Writing

- [The Kamailio Internals Handbook I Wrote With an LLM — and Why I Think It's Worth Your Time](https://denys-pozniak.medium.com/the-kamailio-internals-handbook-i-wrote-with-an-llm-and-why-i-think-its-worth-your-time-28a2a6c78914) — 2026
- [OpenSIPS anycast SIP balancer](https://denys-pozniak.medium.com/opensips-anycast-sip-balancer-c0e9e8884eb) — 2023
- [Kamailio registration replication with DMQ](https://denys-pozniak.medium.com/kamailio-registration-replication-with-dmq-be3b9b8478d) — 2019

[More on Medium →](https://denys-pozniak.medium.com/)

---

## 📫 Connect with Me

Working through a VoIP or voice AI architecture question? Feel free to reach out — always glad to share what I've learned from running these systems in production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/denyspozniak/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://denys-pozniak.medium.com/)

---

## 💼 About My Work

I specialize in designing and implementing scalable VoIP solutions with modern DevOps practices. My approach combines deep protocol-level knowledge with cloud-native infrastructure automation, ensuring robust and efficient telecommunications systems.

**Key Areas:**
- 🏗️ VoIP Infrastructure Architecture
- 🔧 Telecommunications Protocol Engineering
- ☁️ Cloud-Native VoIP Deployments
- 🔄 CI/CD for Telecom Systems
- 📊 Network Design & Optimization

---

## 🤝 Open Source Contributions

Code of mine is merged upstream in the projects I work with every day:

[![Kamailio](https://img.shields.io/badge/Kamailio-1A6FB5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kamailio/kamailio)
[![OpenSIPS](https://img.shields.io/badge/OpenSIPS-0A7E8C?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OpenSIPS/opensips)
[![rtpengine](https://img.shields.io/badge/rtpengine-8B5E00?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sipwise/rtpengine)

---

## 📖 Featured Projects

### [kamailio-handbook](https://denyspozniak.github.io/kamailio-handbook/)
Deliberately **not** a cookbook — the official docs and the wiki already cover installation and module reference. This one is about the internals: what processes Kamailio forks at startup, how `pkg` and `shm` memory differ, how a SIP message threads through the routing engine, how KEMI bridges C and Lua, and what `topos` and `dmq` actually do underneath. English and Ukrainian.

### [sems-handbook](https://denyspozniak.github.io/sems-handbook/)
The companion volume, same treatment for SEMS. Kamailio owns the signalling plane; SEMS owns the media plane and the B2BUA — read together they cover both. 56 chapters in English and Ukrainian: the thread model (SEMS is threads, not processes), its own SIP stack, `AmSession`, the media processor and its 10 ms tick, the SBC framework, security, production topologies, and where the forks diverged.

### [OpenSIPS Hover](https://open-vsx.org/extension/denyspozniak/opensips-hover)
A Cursor / VS Code extension that brings the official OpenSIPS documentation into your editor — hover any keyword in `opensips.cfg` and get module, modparam, function, pseudo-variable and transformation docs inline. [Source](https://github.com/denyspozniak/vscode-opensips-hover)

### [pcapsipdump](https://github.com/denyspozniak/pcapsipdump) 🚧
A long-time favourite of mine that went quiet on SourceForge — and one I'm going to try to bring back to life. A libpcap sniffer that writes **one `.pcap` per SIP call** — signalling plus the RTP/RTCP that belongs to it — instead of one giant capture. First steps are done: modern build, CI and Debian packaging, tagged v1.2.0.
