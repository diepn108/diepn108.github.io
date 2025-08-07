---
layout: post
title: "Solar Study: SEMS and DERMS in Vietnam and the U.S."
subtitle: "From Rooftop Challenges in Vietnam to Smart Grid Solutions in the U.S."
author: Ngoc Diep Nguyen
tags: [solar energy, SEMS, DERMS, smart grid, CPCEMEC, Vietnam, renewable energy]
categories: [grid-control]
comments: true
mathjax: true
---

## From SEMS to DERMS – Managing Distributed Renewable Energy Resources 

During my one-month internship at CPC EMEC, I had the opportunity to collaborate with the team on researching and writing a paper about the **Solar Energy Management System (SEMS)**. While working on that IEEE paper, I came to realize that rooftop solar systems in Vietnam face several limitations and challenges that need to be addressed. This sparked my interest in exploring how similar systems are managed in the United States, leading me to study SEMS in the U.S. and eventually the more advanced **Distributed Energy Resource Management Systems (DERMS)**.

---

## 1. Rooftop Solar Systems in Vietnam: Rapid Growth, New Challenges

In recent years, rooftop solar power systems in Vietnam have experienced explosive growth. However, the majority of these installations are small-scale and highly distributed, leading to inefficiencies in centralized control. When weather conditions are unfavorable, many rooftop systems fail to synchronize with the main grid, causing power shortages and instability for connected loads.

To address these challenges, **CPC EMEC introduced the Solar Energy Management System (SEMS)** — a centralized monitoring and control platform. SEMS supports communication with various inverter brands currently available in Vietnam, enabling:

- Real-time data collection  
- Remote power curtailment  
- Advanced performance analytics  

This system provides an effective smart grid management solution, ensuring timely power delivery during disruptions and enabling efficient monitoring of distributed energy sources. As a result, the system has seen many real-life applications in recent months.

## 2. Effective Management of Renewable Energy in the U.S.: The Rise of DERMS

Meanwhile, in the United States, **Distributed Energy Resource Management Systems (DERMS)** are being widely deployed to manage increasingly complex energy networks. Key capabilities include:

### 2.1 Model-Predictive Control (MPC) & Network-Aware DER Optimization
- Uses mathematical models to predict grid states and avoid overloads  
- Optimizes DER behaviors including batteries, inverters, and flexible loads  
- Adapts to distribution network topology (feeders, nodes, etc.)  
- _Example_: **DERMS-RT**, **FAST-DERMS** (using RT-OPF algorithms for real-time control)

### 2.2 Learning-Based DER Controls
- Applies machine learning to historical data, weather, and user load behavior  
- Enhances state estimation and demand forecasting  
- _Example_: **Predictive State Estimation**, **EdgeFlex**

### 2.3 DER-Aware Distribution Network Management & Automation
- Automates voltage regulation, fault detection, and isolation  
- Combines ADMS with DERMS for **self-healing grid operations**  
- _Example_: **Grid-Edge Intelligent Distribution Automation**, **ADMS Integration**

### 2.4 Community Microgrid Control for Resilience
- Enables operation in island mode during outages  
- Connects solar, batteries, and controllable loads into flexible microgrids  
- _Example_: **Resilience-Oriented Cellular Grid**, **Hierarchical Net-Zero Control**, **IDMS**

### 2.5 Architecture Design & Algorithm Integration with Commercial Platforms
- Develops **scalable federated architectures**  
- Ensures vendor-neutral interoperability via IEEE 2030.5 and OpenFMB  
- _Example_: **FAST-DERMS**, **ADMS Test Bed**, **Community DER Integration**

## 3. Selected DERMS Projects by NREL (U.S.)

- **Basalt Vista Project**: Real-time power flow optimization for community DERs in Colorado  
- **DERMS for PV Hosting Capacity**: Avoiding grid upgrades with inverter optimization  
- **EdgeFlex**: Estimating and using DER flexibility at grid edges  
- **Hierarchical Control in Net-Zero Communities**: Aggregating behind-the-meter DERs  
- **Networked DERs for Community Resilience**: Load restoration with DERs  
- **Self-Healing Distribution Grid**: Fault detection, isolation, and restoration  
- **Resilience-Oriented Cellular Grid**: Microgrid design for rural energy resilience  
- **FAST-DERMS**: Secure, scalable architecture for full-spectrum DER management

## 4. Key Takeaways

- Vietnam’s SEMS is a strong step toward rooftop solar integration, yet lacks predictive and market-based control seen in U.S. DERMS  
- U.S. DERMS implementations focus on intelligent control, automation, and real-time optimization of DERs  
- Coordination between grid operators and consumers through **MPC + real-time control** is crucial for reliable distributed power systems  

## 5. References

- [National Renewable Energy Laboratory (NREL)](https://www.nrel.gov)  
- [IEEE Smart Grid Standards](https://smartgrid.ieee.org)  
- CPC EMEC SEMS Platform (Vietnam)  
- [IEEE Xplore Digital Library](https://ieeexplore.ieee.org)  
- IEEE 2030.5 and OpenFMB Protocol Specifications  
