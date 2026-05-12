---
title: "Research"
permalink: /research/
classes: wide
pagination: false
related: false
---

## Current Focus

### Network Digital Twin  
**Role:** Core system design & implementation  
**Links:** [NDTwin website](https://ndtwin.org/)

**What:**  
NDTwin is an open-source Network Digital Twin system that provides real-time network observability, high-precision flow-level telemetry, simulation-based analysis, and closed-loop network control.

**Why:**  
Modern network operators need more than passive monitoring. They need actionable, real-time visibility into network states, the ability to evaluate “what-if” scenarios before making changes, and scalable mechanisms to apply control decisions with low overhead.

**How:**  
- Modular architecture: collector, monitor, controller, applications, tools, and UI/website  
- High-precision flow-level and per-link telemetry using sFlow/OpenFlow-based data collection  
- General simulation platform for testing network scenarios and application logic  
- Closed-loop workflow: collect network states -> model the network -> run simulations/analysis -> apply control actions  
- Evaluations on physical testbeds, emulation environments, and/or traces to study accuracy, overhead, and scalability