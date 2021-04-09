---
layout: default
title: Home
nav_order: 1
description: "Pi-KVM IP-KVM"
permalink: /
---
<img src="./assets/images/logo-black.svg" width="200"/>
# IP-KVM based on Raspberry Pi
[![Discord](https://img.shields.io/discord/580094191938437144?logo=discord)](https://discord.gg/bpmXfz5) [![Reddit](https://img.shields.io/badge/reddit-join-orange?logo=reddit)](https://www.reddit.com/r/pikvm)

A very simple and fully functional Raspberry Pi-based KVM over IP. This device helps to manage servers or workstations remotely, regardless of the health of the operating system or whether one is installed. You can fix any problem, configure the BIOS, and even reinstall the OS using the virtual CD-ROM or Flash Drive.

## Features
* Supported **Raspberry Pi 2**, **3**, **4** and **ZeroW**;
* **FullHD video** using advanced **HDMI-to-CSI bridge** or **USB dongle**;
* Extra low **100ms video latency** (for CSI bridge);
* Bootable **Virtual CD-ROM** and **Flash Drive**;
* USB **Keyboard** and **mouse** (with leds and the wheel), PS/2 keyboard, Bluetooth HID;
* **Control the server power** using ATX functions;
* Access via **Web UI** or **VNC**;
* Ability to use **IPMI BMC**, **IPMI SoL**, **Redfish** and **Wake-on-LAN** to control the server;
* **The ready-made OS** with read-only filesystem;
* **Extensible authorization** and SSL encryption;
* **Health monitoring** of the Pi;
* Control **GPIO** ports and **USB relays**;
* Packages only costs between $30 and $100 for parts!
* 100% Open Source!

## Open Source
* **The Website**  
  Visit the website to get the latest info [pikvm.org](https://pikvm.org).
* **Community & support**  
  Pi-KVM has a large community. Join the [discord chat](https://discord.gg/bpmXfz5) for news, questions and support!
* **Extensible**  
  Pi-KVM was designed as a set of microservices with a plug-in architecture. It's very easy to modify and maintain.<!---TODO: Link to all microservices page--->
* **Comprehensive API**  
  Everything that can be done via the user interface can also be done via a powerful HTTP API.<!---TODO: Link to API info--->
* **Know-how**  
  We created [our very own MJPG video server](https://github.com/pikvm/ustreamer) written in C with multi-threading support and GPU video encoding - the fastest streaming solution available to provide the best video quality for Pi-KVM. We also tested a lot of hardware configurations so that you can be sure devices you assemble will work reliably.<!---TODO: Possible link to MJPG info--->
