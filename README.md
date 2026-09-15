<!--
  Profile README for PolishMen25
-->

<h1 align="center">PolishMen25</h1>
<p align="center">
  <strong>Infrastructure · Systems · Networks · Virtualization · Local AI</strong>
</p>
<p align="center">
  Building private, resilient and well-documented IT environments — from hardware and network design to self-hosted services and sovereign AI.
</p>

<p align="center">
  <a href="https://polishmen25.github.io">IT Portfolio</a>
  ·
  <a href="https://polishmen.fr">Portfolio</a>
  ·
  <a href="https://github.com/PolishMen25/sovereign-local-ai">Sovereign Local AI</a>
</p>

```text
$ whoami
IT-focused builder working across systems administration, network infrastructure,
virtualisation, cybersecurity fundamentals, automation and locally controlled AI.
```

## Current focus

- Designing practical, secure infrastructure for real workloads.
- Running and documenting a personal homelab: compute, storage, virtualisation and networking.
- Building **Sovereign Local AI** — a CPU-only, privacy-first AI platform with explicit trust boundaries.
- Improving reliability through clear architecture, repeatable processes and automation.

## Technical landscape

<p>
  <img src="https://img.shields.io/badge/Proxmox-0B0F19?style=for-the-badge&logo=proxmox&logoColor=E57000" alt="Proxmox" />
  <img src="https://img.shields.io/badge/Linux-0B0F19?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux" />
  <img src="https://img.shields.io/badge/Windows_Server-0B0F19?style=for-the-badge&logo=windows&logoColor=00A4EF" alt="Windows Server" />
  <img src="https://img.shields.io/badge/Docker-0B0F19?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/PowerShell-0B0F19?style=for-the-badge&logo=powershell&logoColor=5391FE" alt="PowerShell" />
</p>

| Area | Technologies & interests |
| --- | --- |
| **Systems** | Linux, Windows Server, Active Directory, identity and service administration |
| **Virtualisation** | Proxmox, virtual machines, resource planning, backup and recovery |
| **Networks** | Switching, VLAN segmentation, VPN/private access, firewall fundamentals and documentation |
| **Storage** | Synology, backup strategy, integrity checks, data lifecycle and controlled access |
| **Automation** | PowerShell, Docker, Git, repeatable configurations and operational documentation |
| **Security** | Least privilege, network isolation, controlled ingestion, auditability and deny-by-default thinking |
| **Local AI** | CPU-only LLM infrastructure, RAG research, data provenance and private deployment |

## Homelab & infrastructure

A hands-on environment for learning, testing and running services deliberately — with reliability and security treated as design requirements.

```text
               private access / VPN
                       │
          ┌────────────┴────────────┐
          │   segmented homelab     │
          └───────┬─────────┬───────┘
                  │         │
        ┌─────────▼──┐  ┌───▼──────────┐
        │ Proxmox    │  │ Synology     │
        │ HPE compute│  │ storage      │
        └─────┬──────┘  └────┬─────────┘
              │              │
              └──────┬───────┘
                     ▼
        private services · backups · local AI
```

**Core themes:** HPE-based compute, Proxmox virtualisation, Synology storage, private services, segmented networking, backup validation and documentation that makes systems maintainable.

## Featured project

### [Sovereign Local AI](https://github.com/PolishMen25/sovereign-local-ai)

A controlled, **CPU-only** local AI platform being designed for privacy, traceability and owner control.

- Private local interface with a usable bootstrap assistant.
- Experimental `CORE-700M` research path, explicitly separated from production claims.
- Strict data lifecycle: external acquisition → quarantine → validation → approved knowledge.
- Clear network trust boundaries: the AI core is designed without direct Internet access.
- Security gates, provenance tracking, reproducible checks and explicit human approval.

> The project is intentionally transparent about what is experimental, what is usable today and what remains gated.

## Principles

```text
Security by design     > security added later
Private by default     > unnecessary exposure
Measured progress      > inflated claims
Documented systems     > tribal knowledge
Owner control          > opaque automation
```

## Connect

- 🌐 [polishmen.fr](https://polishmen.fr)
- 💻 [GitHub projects](https://github.com/PolishMen25?tab=repositories)
- 💬 Open to discussing infrastructure, homelabs, virtualisation, network design and local AI.

<p align="center">
  <sub>Built with a systems mindset: deliberate, observable and secure by default.</sub>
</p>
