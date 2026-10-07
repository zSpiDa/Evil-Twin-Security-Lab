# Evil Twin Wi-Fi Security Lab

Academic cybersecurity project exploring an **Evil Twin Wi-Fi attack scenario** through a controlled laboratory simulation, with a focus on wireless networking, traffic analysis, social engineering, the Cyber Kill Chain, and defensive countermeasures.

> **Disclaimer**
>
> This project was developed exclusively for educational purposes in a controlled academic environment.
> The MSC brand and related visual references were used solely to create a realistic fictional scenario.
> This project is not affiliated with or endorsed by MSC Cruises and makes no claims regarding the actual security of MSC systems or infrastructure.
>
> No malicious executable or functional payload is distributed in this repository.

## Overview

The project investigates how an Evil Twin wireless network can be combined with a captive portal and social engineering techniques to simulate a multi-stage cybersecurity attack.

The scenario was structured around the **seven phases of the Cyber Kill Chain**, considering both offensive techniques and defensive controls.

The hands-on laboratory activities included configuring a wireless access point, DHCP and DNS services, analyzing network traffic with Wireshark, implementing a captive portal scenario, and demonstrating reverse-shell behavior in a controlled environment.

## Lab Activities

### Evil Twin Access Point

A fake wireless access point was configured using **hostapd**, including SSID and wireless network settings, to reproduce the behavior of an open guest Wi-Fi network.

The project also examined how **Wireless Intrusion Prevention Systems (WIPS)** can identify unauthorized access points and how deauthentication frames may be used as part of a defensive response.

### Network Configuration & Captive Portal

The laboratory environment included the configuration of:

- DHCP address assignment
- default gateway
- DNS
- traffic redirection
- captive portal

These components were used to reproduce the network flow of an Evil Twin scenario in a controlled environment.

### Traffic Analysis

**Wireshark** was used to inspect network traffic and analyze IEEE 802.11 deauthentication frames in the context of wireless intrusion detection and response.

### Social Engineering

The project examined the human component of Evil Twin attacks by studying how a familiar-looking wireless network and captive portal could influence a user into trusting an unauthorized network.

The cruise-line-inspired interface was used only to provide a realistic fictional context for the academic simulation.

### Cyber Kill Chain Simulation

The scenario was analyzed according to the seven stages of the **Cyber Kill Chain**:

1. Reconnaissance
2. Weaponization
3. Delivery
4. Exploitation
5. Installation
6. Command and Control
7. Actions on Objectives

A reverse-shell connection was also demonstrated in the controlled laboratory environment using common security tools.

The executable used during the academic exercise is intentionally **not included** in this repository.

## Defensive Analysis

The project considered defensive controls at different stages of the simulated attack, including:

- Wireless Intrusion Prevention Systems (WIPS)
- wireless monitoring
- Windows SmartScreen
- antivirus protection
- Endpoint Detection and Response (EDR)
- security awareness
- threat intelligence

This provided both an offensive and defensive perspective on the simulated attack lifecycle.

## Tools & Concepts

- Kali Linux
- Wireshark
- hostapd
- Netcat
- Msfvenom
- DHCP / DNS
- TCP/IP & wireless networking
- Captive portals
- Cyber Kill Chain
- Social Engineering
- WIPS
- EDR

## Documentation

The repository includes the original academic documentation and presentation, revised for public portfolio use.

- **Project Report** — detailed description of the scenario, laboratory activities and defensive analysis
- **Project Presentation** — presentation used to illustrate the Cyber Kill Chain and the simulated attack scenario

## What I Learned

This project provided hands-on experience with:

- wireless networking and security fundamentals
- Evil Twin attack scenarios
- access point configuration
- DHCP and DNS configuration
- network traffic analysis
- captive portal concepts
- social engineering risks
- the Cyber Kill Chain framework
- endpoint and wireless defensive controls
- offensive and defensive security perspectives

## Authors

- Daniele Spinelli
- Simone Albano
- Francesco Liuzzi
- Gabriele Bicaku

Academic project developed at the **University of Bari Aldo Moro**.
