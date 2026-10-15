# Maksym Vasylchenko · nagual2

**Linux System Administrator & Network Engineer** · Deutschland

OpenWrt multi-WAN, IPv6 architecture, VPN/tunneling, SSH3/QUIC, MCP tooling, and automation for production routers.

[English](#english) · [Deutsch](#deutsch) · [Русский](#русский)

---

## English

### Focus

- **Multi-WAN / failover** — mwan3 policy routing, health checks, IPv6 over WireGuard and tunnel brokers
- **IPv6** — NPTv6, prefix delegation, split-default routing, HE/6in4 integration
- **OpenWrt** — custom packages, LuCI extensions, opkg/apk builds, prod/dev lab workflows
- **SSH3 / QUIC** — HTTP/3-based remote shell: upstream Go forks (`ssh3-go`, `quic-go`), SSH3 transports in tooling
- **MCP tooling** — unified SSH MCP server with a host registry (direct, SSH3/QUIC and WSL-proxied transports)
- **AI-assisted engineering (vibecoding)** — agentic CLI workflows as a first-class dev process: repo rules & skills, plan → tests → code loops, multi-agent orchestration
- **Local LLM stack** — Ollama models and embeddings, agent memory (`echovault`), custom MCP servers
- **Automation** — Perl, Bash, Python, PowerShell; CI-friendly packaging and deploy scripts

### Background

20+ years of system administration and networking: ISP operations, high-load hosting on Nginx, VPN infrastructure, monitoring (Nagios, Grafana); FreeBSD/Linux administration, Perl/Mojolicious and Python development; the last decade — technical support engineering in fintech.

### Core stack

![Linux](https://img.shields.io/badge/Linux-Admin-FCC624?logo=linux&logoColor=black)
![FreeBSD](https://img.shields.io/badge/FreeBSD-Admin-AB2B28?logo=freebsd&logoColor=white)
![OpenWrt](https://img.shields.io/badge/OpenWrt-Networking-00B5AD?logo=openwrt&logoColor=white)
![IPv6](https://img.shields.io/badge/IPv6-Multi--WAN-0052CC)
![SSH3](https://img.shields.io/badge/SSH3-HTTP%2F3%20over%20QUIC-673AB7)
![MCP](https://img.shields.io/badge/MCP-Agent%20Tooling-7B2FBE)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-0F172A?logo=ollama&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A)
![Bash](https://img.shields.io/badge/Bash-Shell-4EAA25?logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-Automation-3776AB?logo=python&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-Mojolicious-39457E?logo=perl&logoColor=white)
![nftables](https://img.shields.io/badge/nftables-fw4-1E5128)
![Docker](https://img.shields.io/badge/Docker-Tools-2496ED?logo=docker&logoColor=white)

### Highlighted projects

| Project | Role |
|---------|------|
| [**mwan6-npt**](https://github.com/nagual2/mwan6-npt) | NPTv6 for multi-WAN OpenWrt — nftables hooks, UCI, hotplug |
| [**mwan3**](https://github.com/nagual2/mwan3) | Fork with IPv6 track-host routes, connected-ipset filter, conntrack helpers |
| [**ssh-hosts-mcp**](https://github.com/nagual2/ssh-hosts-mcp) | Unified SSH MCP server with a host registry — direct, SSH3 (QUIC) and WSL-proxied transports |
| [**luci-app-netbird**](https://github.com/nagual2/luci-app-netbird) | NetBird package for OpenWrt 25.x — prebuilt apk, PR to openwrt/packages |
| [**mwan6-npt-luci**](https://github.com/nagual2/mwan6-npt-luci) | LuCI UI for NPTv6 Multi-WAN |
| [**luci-app-mwan3**](https://github.com/nagual2/luci-app-mwan3) | Extended mwan3 LuCI (IPv6 multi-tunnel options) |
| [**luci-proto-wireguard-ip6prefix**](https://github.com/nagual2/luci-proto-wireguard-ip6prefix) | WireGuard `ip6prefix` field in LuCI |
| [**openwrt-captive-monitor**](https://github.com/nagual2/openwrt-captive-monitor) | Captive portal automation (OpenWrt + Docker/Selenium) |

### Also maintained

- [luci-i18n-mwan3-ru](https://github.com/nagual2/luci-i18n-mwan3-ru) · [luci-i18n-mwan6-npt-ru](https://github.com/nagual2/luci-i18n-mwan6-npt-ru) — Russian LuCI translations
- [openwrt-extended-backup](https://github.com/nagual2/openwrt-extended-backup) — extended OpenWrt backup tooling
- [ssh3-go](https://github.com/nagual2/ssh3-go) · [quic-go](https://github.com/nagual2/quic-go) — SSH3 and QUIC Go forks (upstream tracking, patches)
- [echovault](https://github.com/nagual2/echovault) — local-first agent memory (fork)

### Lab environment

Production and dev OpenWrt routers (x86/64), Hyper-V and WSL2 sandboxes, SSH-driven deploy and validation matrices for firewall hooks, mwan3 policy and SSH3 transports.

---

## Deutsch

**Senior Infrastructure / Netzwerk-Ingenieur** mit Schwerpunkt auf eingebettete Router, IPv6 und Multi-WAN-Betrieb.

- OpenWrt-Pakete und LuCI-Erweiterungen für **mwan3** und **NPTv6**
- IPv6-Architektur: WireGuard, Tunnelbroker, Policy Routing, nftables/fw4
- **SSH3 (HTTP/3 über QUIC)** — Go-Forks, SSH3-Transports im Tooling
- **MCP-Tooling** für Netzwerkautomation (SSH-Host-Registry, direkte und WSL-proxiierte Verbindungen)
- **KI-gestützte Entwicklung (Vibecoding)** — agentische CLI-Workflows als fester Teil des Dev-Prozesses: Repo-Regeln und Skills, Plan–Test–Code-Schleifen, Multi-Agenten-Orchestrierung
- **Lokale LLM-Infrastruktur** — Ollama-Modelle und Embeddings, Agent-Gedächtnis (`echovault`), eigene MCP-Server
- Automatisierung von Build, Deploy und Tests (Bash, Python, PowerShell)

Über 20 Jahre Systemadministration und Netzwerke: ISP-Betrieb, Hochlast-Hosting auf Nginx, VPN-Infrastruktur, FreeBSD/Linux-Administration, Perl/Mojolicious- und Python-Entwicklung; das letzte Jahrzehnt — Support-Engineering im Fintech.

Wichtigste öffentliche Repositories siehe Tabelle oben.

---

## Русский

Инженер по Linux и сетям: OpenWrt, **multi-WAN**, **IPv6**, VPN, **SSH3/QUIC**, MCP-инструментарий и автоматизация. Рабочий процесс — **вайбкодинг**: агентские CLI-сценарии, правила и skills репозитория, мульти-агентная оркестрация; локальный LLM-стек (Ollama, embeddings) и память агентов (`echovault`).

20+ лет системного администрирования и сетей: ISP, high-load хостинг на Nginx, VPN-инфраструктура, FreeBSD/Linux, разработка на Perl/Mojolicious и Python; последнее десятилетие — support-инжиниринг в финтехе.

Основные открытые проекты — **mwan3**, **mwan6-npt**, **ssh-hosts-mcp**, **luci-app-netbird** и связанные LuCI-пакеты для продакшен-роутеров с несколькими туннелями.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nagual2&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
</p>
