## Currently organizing the code to be less messy. If wanting access or discuss about code, please visit https://rafalkrzysiak.github.io/ for contact info. I will be more than happy to respond.

# 🧪 Benchtop Thermal Imager

A compact, Raspberry Pi-powered thermal imaging system built for benchtop use. It features the **Adafruit MLX90640 IR Thermal Camera (55° FOV)**, a **Raspberry Pi 4B**, and a **7" capacitive touch display**, all integrated into a simple user-friendly setup. Designed for educational, DIY, and light industrial applications.

![thermal-imager-demo](assets/thermal_imager_demo.jpg) <!-- Replace with actual image path -->

---

## 🔧 Hardware Components

| Component | Description |
|----------|-------------|
| 🖥️ **Raspberry Pi 4B** | 2GB/4GB/8GB (any variant works), running RPi OS |
| 🌡️ **Adafruit MLX90640 IR Thermal Camera** | 32×24 thermal resolution, 55° field of view |
| 📱 **7" Capacitive Touchscreen Display** | 1024×600 resolution with touch support |
| 🔌 Power Supply | 5V 3A USB-C for Raspberry Pi |
| 🖼️ Mount/Enclosure | Custom 3D-printed and aluminum extrusion (optional) |

---

## 🚀 Features

- Real-time thermal imaging display
- Touchscreen-enabled user interface
- Temperature readout at center or user-tapped location
- Adjustable color maps (e.g., inferno, jet, gray)
- Optional data logging mode (CSV or image snapshots)
- Frame rate: ~2Hz (depends on processing settings)

---

## 📷 Live Demo

<p align="center">
  <img src="assets/thermal_imager_screen.gif" width="400"/>
</p>

---

## 📁 Repository Structure

```bash
benchtop-thermal-imager/
├── src/                      # Main Python source code
│   └── thermal_viewer.py     # Viewer application
├── assets/                   # Images, GIFs, screenshots
├── requirements.txt          # Python dependencies
├── setup.md                  # Setup & hardware wiring guide
└── README.md
