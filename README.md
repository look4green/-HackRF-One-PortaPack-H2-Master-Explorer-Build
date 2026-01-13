# HackRF One + PortaPack H2 & H4M "Master Explorer" Build

This repository documents the custom assembly and configuration of a high-gain, wide-band SDR field unit. This build is designed for full-spectrum exploration from 10kHz to 6GHz.

## 🛠 Hardware Specifications
* **Base Unit:** HackRF One (SDR Transceiver)
* **Expansion:** PortaPack H2 (IPS Display & Touchscreen)
* **Enclosure:** Integrally formed Aluminum Alloy Case (RF Shielded)
* **Audio:** Custom Internal Speaker Upgrade
* **Firmware:** Mayhem v2.2.0 (Stable)

## 📡 Antenna Master Kit
To cover the full range of the HackRF, the following antennas are used:

| Antenna | Frequency Range | Purpose |
| :--- | :--- | :--- |
| **RH770 Telescopic** | 144 / 430 MHz | High-gain scanning (Police, Ham, FM) |
| **UWB Log Periodic** | 1.3GHz - 10GHz | Directional hunting (Wi-Fi, Bluetooth, 5G) |
| **Broadband Donut** | 10kHz - 180MHz | Active LF/HF (Shortwave & AM Radio) |
| **EZCOM Adapter** | N/A | SMA-Male to BNC-Female port saver |

## 🚀 Mayhem v2.2.0 Key Features
This build utilizes the **v2.2.0 firmware**, which includes:
* **Dual-Channel Spectrum:** Monitor two bands side-by-side.
* **Enhanced ADS-B:** High-res map tiles and altitude color gradients.
* **GPIO Manager:** In-firmware UI to configure expansion modules.
* **Battery Health:** Built-in cycle tracking and wear level monitoring.
* **Performance:** Reduced encoder lag and optimized power management.

## 📂 SD Card Structure
Ensure your MicroSD card (FAT32/exFAT) contains the following directories for v2.2.0:
* `/ADSB/` - Map tiles and flight data.
* `/CAPTURES/` - Raw IQ recordings.
* `/FREQMAN/` - Frequency list files.
* `/LOGS/` - System and signal logs.
* `/WATERFALLS/` - Custom color gradients.

## ⚠️ Safety & Compliance
* **Receive Only:** Ensure local regulations are followed when listening to specific bands.
* **Transmit:** Only transmit on frequencies you are licensed for (e.g., Amateur Radio bands).
* **Power:** Charge via USB-C (5V/1A). Do not exceed the voltage limits of the Portapack charging circuit.

---
*Built for the curiosity of the invisible world.*
