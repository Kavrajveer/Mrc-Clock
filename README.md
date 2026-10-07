# MRC Clock ⏰

A custom, open-hardware smart alarm clock designed for the **Hack Club BLARE** challenge. Built entirely using mobile browser workflows! 🚀

---

## 🛠️ Hardware Specifications

* **Microcontroller:** Seeed Studio XIAO ESP32-C3
* **Display:** 2.25″ SPI TFT LCD Screen
* **Audio:** Piezo Buzzer
* **Inputs:** 2× Tactile Push Buttons (Snooze & Set)
* **Power:** 5V via USB-C

---

## 📌 Pin Mapping

| Peripheral | Function / Pin | ESP32-C3 GPIO |
| :--- | :--- | :--- |
| **Display** | SPI MOSI | GPIO 6 |
| **Display** | SPI SCK | GPIO 4 |
| **Display** | CS | GPIO 7 |
| **Display** | DC | GPIO 2 |
| **Display** | RESET | GPIO 1 |
| **Buzzer** | Signal (+) | GPIO 3 |
| **Button 1** | Snooze / Action | GPIO 0 |
| **Button 2** | Set / Menu | GPIO 5 |

---

## 📂 Repository Structure

* `/gerber/` — Exported Gerber manufacturing ZIP file for PCB fabrication.
* `/cad/` — OpenSCAD source files and watertight `.stl` 3D-printable enclosure models.
* `/src/` — ESP32 firmware configured for NTP WiFi time synchronization and alarm logic.
* `/screenshots/` — Schematic, board routing, and 3D preview screenshots.

---

## 💡 Engineering Notes

* Designed directly in mobile browser environments (EasyEDA Web & OpenSCAD Web).
* Features internal M3 mounting standoffs, rear USB-C port access, and front-facing screen cutouts.
* Firmware utilizes open-source NTP and Adafruit GFX display libraries adapted for this custom pin layout.
