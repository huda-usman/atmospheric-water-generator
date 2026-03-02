# 💧 Water Extractor from Air

<div align="center">

![Status](https://img.shields.io/badge/Status-Working%20Prototype-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Hardware%20Project-orange?style=for-the-badge)
![No Code](https://img.shields.io/badge/Code-None%20Required-lightgrey?style=for-the-badge)

> **Harvesting water from thin air — using the power of thermoelectrics.**

</div>

---

## 🌊 Overview

This project demonstrates a **mini atmospheric water generator (AWG)** that extracts moisture directly from ambient air and converts it into liquid water droplets — **no coding required**, purely electronics and thermodynamics.

Built as a **semester project for Digital Logic Design (DLD)**, it showcases the practical application of the **Peltier (thermoelectric) effect** to cool a surface below the **dew point**, causing water vapor in the air to condense and drip into a collection container.

---

## 📸 Project Gallery

| Front View | Side View | Back View |
|:---:|:---:|:---:|
| ![Front](IMG_8144.jpg) | ![Side](IMG_8145.jpg) | ![Back](IMG_8146.jpg) |
| *Condensation visible on fins* | *Fan & full assembly* | *Water collected in container* |

> 💦 The water droplets visibly forming on the heatsink fins confirm the system is working!

---

## ⚙️ How It Works

```
 Humid Air
    │
    ▼
┌─────────────┐
│  Cooling Fan │  ◄── Pushes air over the cold heatsink
└──────┬──────┘
       │
       ▼
┌─────────────────────┐
│   Cold Heatsink      │  ◄── Temperature drops below Dew Point
│  (Peltier Cold Side) │       → Moisture condenses on fins
└──────┬──────────────┘
       │  Water Droplets drip down
       ▼
┌─────────────┐
│  Collection  │  ◄── Plastic container catches the water
│  Container   │
└─────────────┘
       │
┌─────────────────────┐
│   Hot Heatsink       │  ◄── Dissipates heat from hot side of Peltier
│  (Peltier Hot Side)  │       + Thermal Paste for better conductivity
└─────────────────────┘
```

### 🧊 The Science Behind It

The **Peltier module** (TEC — Thermoelectric Cooler) works on the **Peltier Effect**:
- When DC current flows through two dissimilar semiconductors, **one side gets cold** and **the other gets hot**
- The **cold side** is attached to a heatsink exposed to ambient air
- When the heatsink surface drops below the **dew point temperature**, water vapor in the air **condenses** into liquid droplets
- Droplets run down the fins by gravity and **drip into the collection container**

---

## 🔩 Components Used

| Component | Purpose |
|-----------|---------|
| 🔲 **Peltier Module (TEC1-12706)** | Creates temperature differential — cold side condenses moisture |
| 🌡️ **Aluminum Heatsink (×2)** | Cold side: condenses water · Hot side: dissipates heat |
| 🌀 **Cooling Fan** | Forces airflow over cold heatsink to maximize condensation |
| 🧴 **Thermal Paste** | Ensures efficient heat transfer between Peltier and heatsinks |
| 🔴⚫ **Power Wires (Red/Black)** | DC power supply connections |
| 🦿 **Metal Stand (4 legs)** | Elevates unit so water drips into container below |
| 📦 **Plastic Container** | Collects the extracted/condensed water |
| 🔩 **Bolts, Zip Ties & Brackets** | Mechanical assembly and securing components |

---

## 🛠️ Build Process

### Step 1 — Prepare the Peltier Module
- Identify **cold side** and **hot side** of the TEC module
- Apply **thermal paste** on both faces for maximum thermal contact

### Step 2 — Mount Heatsinks
- Attach **large heatsink** to the **cold side** (this is where condensation occurs)
- Attach **second heatsink** to the **hot side** (for heat dissipation)
- Secure tightly using bolts and metal brackets

### Step 3 — Attach the Cooling Fan
- Mount fan on the **hot side heatsink** to actively exhaust heat away
- Connect fan wires alongside the Peltier power wires

### Step 4 — Assemble the Frame
- Mount the full heatsink + Peltier assembly onto the **4-legged metal stand**
- Ensure enough clearance beneath the cold heatsink for water to drip freely

### Step 5 — Place Collection Container
- Position the **plastic container** directly under the cold heatsink fins
- Water droplets will naturally fall into it by gravity

### Step 6 — Power It Up
- Connect **red wire (+)** and **black wire (−)** to a suitable **DC power supply**
- The Peltier typically runs on **12V DC**
- After a few minutes, condensation will begin forming on the cold heatsink fins 💧

---

## 📊 Specifications

| Parameter | Value |
|-----------|-------|
| Operating Voltage | 12V DC |
| Peltier Module | TEC1-12706 (typical) |
| Condensation Principle | Dew Point / Thermoelectric Cooling |
| Water Output | Depends on ambient humidity & temperature |
| Coding Required | ❌ None |
| Power Source | DC Adapter / Power Supply |

---

## 🌍 Real-World Applications

- 🏜️ **Water harvesting in arid/dry regions**
- 🏕️ **Survival & off-grid water generation**
- 🌱 **Small-scale irrigation in remote areas**
- 💡 **Proof-of-concept for large-scale AWG systems**
- 🎓 **Educational demonstration of thermoelectric effects**

---

## ✅ Results

> After powering the device, visible **water droplets** formed on the heatsink fins within minutes. Droplets accumulated and dripped into the plastic collection container — confirming successful **moisture extraction from ambient air**.

---

## 📁 Repository Structure

```
💧 water-extractor-from-air/
├── 📸 images/
│   ├── IMG_8144.jpg       # Front view — condensation on fins
│   ├── IMG_8145.jpg       # Side view — full assembly
│   └── IMG_8146.jpg       # Back view — water collected
└── 📄 README.md           # This file
```

---

## 🚀 Future Improvements

- [ ] Add a **humidity & temperature sensor** (DHT11/DHT22) with LCD display
- [ ] Use a **larger Peltier module** for higher water output
- [ ] Integrate **solar panel** for off-grid operation
- [ ] Add a **water level sensor** and LED indicator
- [ ] 3D-print a proper enclosure

---

## 📚 References & Concepts

- [Peltier Effect — Wikipedia](https://en.wikipedia.org/wiki/Thermoelectric_effect)
- [Atmospheric Water Generation](https://en.wikipedia.org/wiki/Atmospheric_water_generator)
- [Dew Point Explained](https://en.wikipedia.org/wiki/Dew_point)

---

## 👤 Author

<div align="center">

**Huda Usman**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hudausman010)

*"Turning air into water — one electron at a time."*

</div>

---

<div align="center">

⭐ **If you found this project interesting, please give it a star!** ⭐

Made as a DLD Semester Project

</div>
