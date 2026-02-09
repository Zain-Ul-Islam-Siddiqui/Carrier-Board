# Parking Access Control Carrier Board (RK3568 Linux Platform)
## Overview

Designed and implemented a high-performance carrier board for a Rockchip RK3568 compute module, targeting smart parking access control systems with support for multiple communication protocols and peripheral devices. The board serves as a centralized controller for barrier gates, ANPR cameras, intercom systems, ticket printers, and access readers in outdoor parking installations.

The system runs embedded Linux and provides a scalable hardware platform for field technicians and system integrators to deploy intelligent parking and access control solutions with wired and wireless connectivity, multimedia support, and industrial-grade reliability.

## Description
This project delivers a commercial-grade carrier board for a quad-core ARM Cortex-A76 based compute module (RK3568), designed specifically for parking access control and automation applications. The board integrates multiple industrial interfaces including Wiegand, RS232, RS485, Ethernet, USB, relay outputs, inductive loop inputs, and camera interfaces.

The carrier board enables real-time interaction with ANPR cameras, QR readers, intercom units, ticket printers, and barrier motors while providing a Linux-based software platform for UI, networking, and cloud connectivity. It supports both HDMI and MIPI-DSI displays with capacitive touch for operator interaction.

Designed for outdoor deployment, the hardware incorporates surge protection, ESD protection, wide-temperature operation, and power backup via Li-ion battery or supercapacitor to ensure continuous operation during power disturbances.

## Key Features
- RK3568 quad-core ARM Cortex-A76 Linux compute platform
- Multi-protocol access control support (Wiegand, RS232, RS485, GPIO, USB, Ethernet)
- Dual Ethernet interfaces for intercom and ANPR camera
- HDMI and MIPI-DSI display support with capacitive touchscreen
- Integrated relay outputs for barrier gate control (8 channels)
- Inductive loop detector inputs (3 channels)
- USB and CSI camera support (CCTV / pinhole camera)
- GSM/LTE connectivity via SIM module
- Wi-Fi and Bluetooth 5.0
- On-board environmental sensors (temperature and humidity)
- Battery / supercapacitor backup power support
- Outdoor-rated design with surge, ESD, and EMI protection
- Hardware status RGB LED and provisioning LEDs

## Technologies
- Rockchip RK3568 Compute Module
- Embedded Linux
- LPDDR4 RAM (minimum 4 GB, expandable)
- eMMC Flash (minimum 32 GB)
- USB 2.0 / 3.0
- Ethernet (10/100/1000 Mbps)
- HDMI + MIPI-DSI
- CSI Camera Interface
- GSM/LTE modem
- RS232 / RS485 / Wiegand
- Relays and opto-isolated GPIO
- Altium Designer

## Contribution
- Carrier board schematic design for RK3568 compute module
- High-speed PCB layout (DDR, HDMI, MIPI, Ethernet)
- Interface expansion for industrial IO (Wiegand, RS232, RS485, relays, GPIO)
- ESD, surge, and protection circuitry design
- Integration of GSM/LTE module and SIM interface
- Hardware bring-up preparation and validation planning

## Access Control Interfaces
Wiegand (1 primary + 1 optional)
RS232 (1 channel)
RS485 (1 channel)
Inductive loop detector (3 inputs)
Barrier gate control relays (8 outputs)
Activation LED (1 GPIO)
Status RGB LEDs (up to 6)

## Cameras & Imaging
ANPR camera via Ethernet
CCTV / pinhole camera via USB or CSI

## User Interface
HDMI display output
MIPI-DSI capacitive touchscreen
Optional action buttons (4 GPIO)
Intercom action button (1 GPIO)

## Connectivity
Dual Ethernet
USB (4 ports)
GSM/LTE with SIM card
Optional Wi-Fi & Bluetooth 5.0

## Audio
Microphone input
Speaker output

## Storage
eMMC (32 GB)
SD card slot (up to 512 GB)

## Electrical Specifications
- CPU: Quad-core ARM Cortex-A76 @ 2.4 GHz
- RAM: 4 GB LPDDR4 (expandable up to 32 GB)
- Storage: 32 GB eMMC + SD card
- Power Input: 12–24 V DC
- Backup Power: Li-ion battery

## Protection:
- Reverse polarity protection
- ESD protection on all IO
- Surge protection on Ethernet and inductive loop inputs
- EMI filtering

## Environmental Specifications
- Operating Temperature: -20°C to +65°C
- Humidity: 0% to 98% (non-condensing)
- Deployment: Outdoor parking systems
- Compliance Targets: CE & FCC

## System Block Diagram
![Alt text](System_Block_Diagram.png)
## Nucleo F411RE (Processor)
![Alt text](Nucleo.webp)
## LoRa Shield (RFM95)
![Alt text](LoRa_Node.png)
