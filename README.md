# Maksym Vasylchenko · nagual2

**Linux System Administrator & Network Engineer** · Deutschland

OpenWrt multi-WAN, IPv6 architecture, VPN/tunneling, embedded networking, and automation for production routers.

[English](#english) · [Deutsch](#deutsch) · [Русский](#русский)

---

## English

### Focus

- **Multi-WAN / failover** — mwan3 policy routing, health checks, IPv6 over WireGuard and tunnel brokers
- **IPv6** — NPTv6, prefix delegation, split-default routing, HE/6in4 integration
- **OpenWrt** — custom packages, LuCI extensions, opkg/apk builds, prod/dev lab workflows
- **Automation** — Bash, Python, PowerShell; CI-friendly packaging and deploy scripts

### Core stack

![Linux](https://img.shields.io/badge/Linux-Admin-FCC624?logo=linux&logoColor=black)
![OpenWrt](https://img.shields.io/badge/OpenWrt-Networking-00B5AD?logo=openwrt&logoColor=white)
![IPv6](https://img.shields.io/badge/IPv6-Multi--WAN-0052CC)
![WireGuard](https://img.shields.io/badge/WireGuard-VPN-88171A)
![Bash](https://img.shields.io/badge/Bash-Shell-4EAA25?logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-Automation-3776AB?logo=python&logoColor=white)
![nftables](https://img.shields.io/badge/nftables-fw4-1E5128)
![Docker](https://img.shields.io/badge/Docker-Tools-2496ED?logo=docker&logoColor=white)

### Highlighted projects

| Project | Role |
|---------|------|
| [**mwan6-npt**](https://github.com/nagual2/mwan6-npt) | NPTv6 for multi-WAN OpenWrt — nftables hooks, UCI, hotplug |
| [**mwan3**](https://github.com/nagual2/mwan3) | Fork with IPv6 track-host routes, connected-ipset filter, conntrack helpers |
| [**mwan6-npt-luci**](https://github.com/nagual2/mwan6-npt-luci) | LuCI UI for NPTv6 Multi-WAN |
| [**luci-app-mwan3**](https://github.com/nagual2/luci-app-mwan3) | Extended mwan3 LuCI (IPv6 multi-tunnel options) |
| [**luci-proto-wireguard-ip6prefix**](https://github.com/nagual2/luci-proto-wireguard-ip6prefix) | WireGuard `ip6prefix` field in LuCI |
| [**openwrt-captive-monitor**](https://github.com/nagual2/openwrt-captive-monitor) | Captive portal automation (OpenWrt + Docker/Selenium) |

### Also maintained

- [luci-i18n-mwan3-ru](https://github.com/nagual2/luci-i18n-mwan3-ru) · [luci-i18n-mwan6-npt-ru](https://github.com/nagual2/luci-i18n-mwan6-npt-ru) — Russian LuCI translations
- [openwrt-extended-backup](https://github.com/nagual2/openwrt-extended-backup) — extended OpenWrt backup tooling
- [echovault](https://github.com/nagual2/echovault) — local-first agent memory (fork)

### Lab environment

Production and dev OpenWrt routers (x86/64), Hyper-V sandboxes, SSH-driven deploy and validation matrices for firewall hooks and mwan3 policy.

---

## Deutsch

**Senior Infrastructure / Netzwerk-Ingenieur** mit Schwerpunkt auf eingebettete Router, IPv6 und Multi-WAN-Betrieb.

- OpenWrt-Pakete und LuCI-Erweiterungen für **mwan3** und **NPTv6**
- IPv6-Architektur: WireGuard, Tunnelbroker, Policy Routing, nftables/fw4
- Automatisierung von Build, Deploy und Tests (Bash, Python, PowerShell)

Wichtigste öffentliche Repositories siehe Tabelle oben.

---

## Русский

Инженер по Linux и сетям: OpenWrt, RouterOS-подобные сценарии, **multi-WAN**, **IPv6**, VPN и автоматизация.

Основные открытые проекты — **mwan3**, **mwan6-npt** и связанные LuCI-пакеты для продакшен-роутеров с несколькими туннелями.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nagual2&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
</p>
