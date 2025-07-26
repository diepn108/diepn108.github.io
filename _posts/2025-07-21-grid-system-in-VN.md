---
layout: post
title: Internship at CPCEMEC – A Glimpse into Vietnam's Smart Metering Technology
subtitle: Learning about the RF Spider System and Automated Electric Meters
gh-badge: [star, fork, follow]
tags: [internship, smart metering, RF Spider, electric meters, CPCEMEC, Vietnam, energy]
categories: [grid-control]
comments: true
mathjax: true
author: Ngoc Diep Nguyen
---

During my summer in Vietnam, I had the opportunity to intern at the Central Power Center – Electronic Measurement Equipment Manufacturing Center (CPCEMEC). There, I learned about the center’s current products, including their specifications, functions, and the technical principles applied in their design. Recently, most households in Vietnam’s Central region have transitioned to using automated electric meters managed by the RF Spider system, which offers numerous benefits and significantly reduces costs compared to the previous manual metering system. Let me introduce some key components of this system in more detail.

## 1. Introduction

RF Spider is an automatic electric meter data collection system that enables remote meter reading without the need for on-site personnel. Data is transmitted to the central server via communication protocols such as RF, PLC, 3G/4G, LoRa, and NB-IoT. After processing, data is stored in a database system for management, storage, billing support, fault alerts, energy loss tracking, and user notifications via applications.

![Introduction](/assets/img/Fig1-post3.png)

The system offers key features such as detailed customer management, DCU and router device management, and meter tracking. It provides a visual display of the unit's electrical grid down to each substation, supports grid monitoring, supplies information about substations for timely issue handling based on alerts, and pinpoints customer/device locations needing service. Notably, the solution has demonstrated effectiveness by saving nearly 2,500 workers and over 150 billion VND per year. It also reduces data entry errors, allows high-productivity input, and completes meter reading and billing within one day.

## 2. RF Spider Data Collection System

![RF-mesh](/assets/img/Fig2-post3.png)

The RF Spider data collection system is structured into multiple layers. Each layer includes RF data routers installed at various locations to reduce the data processing load on the DCU (Data Concentrator Unit). Additionally, RF repeater routers are used in transmission to the DCU to enhance efficiency and maintain accuracy during data reading from electric meters.

![Full System](/assets/img/Fig3-post3.png)

## 3. Electronic Meters

The electronic meter products, comprising 28 types with various features, are entirely researched, designed, tested, manufactured, and deployed by CPCEMEC engineers to meet the energy measurement needs of consumers.

![All types of smart meter](/assets/img/Fig3-post4.png)

### Single-phase Electronic Meters

**DT01P-RF:** A single-phase, two-wire meter for direct connection, measuring kWh. Supports RF communication, secure data storage via EEPROM, and displays on an LCD.

- Specs: Rated voltage 220V, max current 40A, accuracy class 1, UART TTL/RF communication (408.925 MHz), -25°C to +60°C operation, IP54 protection.

![Type1](/assets/img/Fig4-post3.png)

**DT01P80-RF:** Measures kWh, current, voltage, power factor. Supports RF, UART TTL, RS232/RS485.

![Type2](/assets/img/Fig5-post3.png)

**DT01M10:** Multi-rate meter with CT connection, measures active/reactive energy in four quadrants, reprogrammable.

![Type3](/assets/img/Fig6-post3.png)

**DT01M80:** Direct connection, measures two-way energy, supports configurable TOU rates.

![Type4](/assets/img/Fig7-post3.png)

### Three-phase Electronic Meters

**DT03P-RF:** Direct connection, four-quadrant energy measurement, detects anomalies.

![Type5](/assets/img/Fig8-post3.png)

**DT03P05:** CT connection, supports four-quadrant measurement, RF and UART TTL.

![Type6](/assets/img/Fig9-post3.png)

**DT03M01:** Multi-rate, CT connection, detects phase/neutral loss, EEPROM storage.

- Specs: 3×(57.7/100–240/415)V, 3×1A nominal, 3×1.2A max, class 0.5S, IP54.

![Type7](/assets/img/Fig10-post3.png)

**DT03M05:** Indirect meter with 3G/4G and PLC support.

![Type8](/assets/img/Fig11-post3.png)

**DT03M10:** Direct meter, supports four-quadrant measurement and advanced comms.

![Type9](/assets/img/Fig12-post3.png)

## 4. Data Concentrator Unit (DCU)

The 1-phase DCU collects, stores, and manages data from up to 1000 RF meters per substation. It transmits via 2G/3G/4G and supports standalone operation with firmware updates.

![DCU](/assets/img/Fig13-post3.png)

## 5. RF Data Router

The Router gathers meter data from up to 250 RF meters and relays it to the DCU, enhancing coverage and reducing processing load.

![Router](/assets/img/Fig14-post3.png)

## 6. RF Signal Repeater Router

Repeats and strengthens RF signals, enabling broader coverage. Supports real-time or scheduled reading and time sync with DCU.
  
![Repeater](/assets/img/Fig15-post3.png)

## 7. Remote Data Collection Modem – RMR Turbojet

A GPRS/3G/4G modem for remote data. Auto-detects meter types, supports push/pull mode, alerts outages, and remote config.

![RMR](/assets/img/Fig16-post3.png)

## 8. Power Quality Monitoring Device – PQM3P

Monitors power quality: kWh, kVarh, voltage, frequency, power factor, etc. Detects anomalies and calculates energy loss.

![PQM3P](/assets/img/Fig17-post3.png)

