# CPNT219 – “FikruNet” Multi‑Site Network Lab

## Overview
Simulation of a **4‑site enterprise network** in Cisco Packet Tracer for CPNT219 (Intro to Networks).  
Each site designed its own **IP addressing (VLSM), cabling, and device configurations**. I owned **Site 3** and contributed to shared team standards.

## Topology & Scope
- **Inter‑site:** “Diamond” router interconnection (R1–R4)
- **Per site:** Router, switch, 5 PCs, WLAN segment
- **Dual‑stack:** IPv4 + IPv6
- **Security baseline:** SSH, console/VTY passwords, password policies

> See `screenshots/` for topology diagrams of Site 1–3.

## My Contributions (Site 3)
- Designed VLSM addressing plan for LANs + point‑to‑point links
- Configured router and switch interfaces for IPv4/IPv6; assigned gateways
- Implemented SSH and password policies for device management
- Documented cabling and produced Site 3 topology diagram

## Validation
- Host to gateway ping (IPv4 & IPv6)
- Inter‑site connectivity across routers
- Verified IPv6 addressing via `show ipv6 interface brief`

See `validation/README.md` for commands.

## Artifacts
- [Final Packet Tracer File](final_project_networking_complete.pkt)
- [Site 1 Topology](site1-topology.png)
- [Site 2 Topology](site2-topology.png)
- [Site 3 Topology](site3-topology.png)

## Lessons Learned
- Building scalable VLSM addressing plans
- Dual‑stack IPv4/IPv6 implementation
- Documenting designs improves collaboration
