# Hackintosh EFI for Medion Akoya **S6446 (MD63420)**

This repository contains the EFI folder and configuration for running macOS via OpenCore on the **Medion Akoya S6446 (MD63420)** laptop.

---

## 💻 System Specifications

| Component        | Details                                                    |
|------------------|-------------------------------------------------------------|
| Model            | Medion Akoya S6446 (MD63420)                                |
| CPU              | Intel Core i5‑8265U (1.6 GHz base, up to 3.9 GHz Turbo) :contentReference[oaicite:0]{index=0} |
| GPU              | Intel UHD Graphics (integrated) :contentReference[oaicite:1]{index=1}       |
| Display          | 15.6″ IPS Full HD (1920×1080) :contentReference[oaicite:2]{index=2} |
| RAM              | 8 GB DDR4‑2400 (upgradable to 64 GB in 2 SO‑DIMM slots) :contentReference[oaicite:3]{index=3} |
| Storage          | 256 GB PCIe M.2 SSD :contentReference[oaicite:4]{index=4}     |
| Wi‑Fi / Bluetooth| Intel AC‑9462 (Wi‑Fi 5 + BT 5.0) :contentReference[oaicite:5]{index=5}     |
| Audio            | Dolby‑certified stereo speakers; built‑in mic :contentReference[oaicite:6]{index=6} |
| Webcam           | Integrated front HD webcam :contentReference[oaicite:7]{index=7} |
| Battery          | 42.6 Wh Li‑Polymer with Rapid‑Charge feature :contentReference[oaicite:8]{index=8} |

---

## ✅ Working Features

- CPU power management  
- Intel GPU acceleration  
- Display brightness & scaling  
- Trackpad & keyboard input  
- Battery status & rapid charge  
- **USB ports are fully mapped**  
- **Webcam functions correctly**  
- **Audio output and mic input are working reliably**  
- Sleep and wake  

---

## ⚠️ Known Issues

- Shutdown doesn’t fully power off: the OS shuts down, but you must **hold the power button for ~5 seconds** to turn off completely.  

---

## ⚙️ BIOS Configuration

Ensure the following BIOS settings:

- Secure Boot: **Disabled**  
- Fast Boot: **Disabled**  
- VT‑d: **Disabled** (unless handled via quirks)  
- CFG Lock: **Disabled** or patched  
- SATA Mode: **AHCI**  
- Boot Mode: **UEFI**

