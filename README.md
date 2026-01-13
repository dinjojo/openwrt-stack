# OpenWRT Stack

A curated **OpenWRT configuration stack** for building a secure, performant, and maintainable router setup.

This repository consolidates firewall hardening, DNS filtering, SQM (QoS), and optional VPN/mesh networking into reusable and modular configurations. Suitable for homelabs, power users, and small networks.

---

## Features

- Hardened OpenWRT firewall rules
- AdGuard Home configuration for DNS-level ad and tracker blocking
- SQM (Smart Queue Management) for bufferbloat control
- Modular and reusable configuration files
- Optional VPN / mesh networking templates
- CLI-first, LuCI-compatible setup

---

## Prerequisites

- Device running OpenWRT
- SSH access to the router
- Basic familiarity with LuCI / UCI
- Internet access for `opkg`

Recommended packages:
- firewall
- iptables
- luci
- sqm-scripts
- luci-app-sqm
- adguardhome

---

opkg install firewall iptables luci
opkg install sqm-scripts luci-app-sqm
opkg install adguardhome

