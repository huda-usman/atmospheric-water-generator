<div align="center">

# 💧 Atmospheric Water Generator

<img src="images/Img_1.jpg" width="400" alt="Water Extractor from Air"/>

<br/>

![Status](https://img.shields.io/badge/Status-Working%20Prototype-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Hardware%20Project-orange?style=for-the-badge)
![No Code](https://img.shields.io/badge/Code-None%20Required-lightgrey?style=for-the-badge)
![Voltage](https://img.shields.io/badge/Power-12V%20DC-red?style=for-the-badge)

### *Harvesting water from thin air — using the power of thermoelectrics.*

</div>

---

## 🌊 Overview

This project is a **mini Atmospheric Water Generator (AWG)** that extracts moisture directly from ambient air and converts it into liquid water droplets — **no coding required**, purely electronics and thermodynamics.

It showcases the practical application of the **Peltier (thermoelectric) effect** to cool a surface below the **dew point**, causing water vapor in the air to condense and drip into a collection container.

---

## 📸 Gallery

<div align="center">

<table>
  <tr>
    <td align="center"><img src="images/Img_1.jpg" width="260"/><br/><sub><b>Front View</b> — Condensation on fins</sub></td>
    <td align="center"><img src="images/Img_2.jpg" width="260"/><br/><sub><b>Side View</b> — Fan & full assembly</sub></td>
    <td align="center"><img src="images/Img_3.jpg" width="260"/><br/><sub><b>Back View</b> — Water collecting below</sub></td>
  </tr>
</table>

> 💦 Water droplets visibly forming on the heatsink fins — the system works!

</div>

---

## ⚙️ How It Works

```
        🌫️  Humid Air
              │
              ▼
     ┌─────────────────┐
     │   Cooling Fan   │  ◄── Forces air over the cold heatsink
     └────────┬────────┘
              │
              ▼
     ┌─────────────────────────┐
     │      Cold Heatsink       │  ◄── Drops below Dew Point
     │   (Peltier Cold Side)    │       → Moisture condenses on fins
     └────────┬────────────────┘
              │  💧 Droplets drip down by gravity
              ▼
     ┌─────────────────┐
     │    Collection    │  ◄── Plastic container catches water
     │    Container     │
     └─────────────────┘

     ┌─────────────────────────┐
     │      Hot Heatsink        │  ◄── Dissipates heat away
     │   (Peltier Hot Side)     │       + Thermal Paste applied
     └─────────────────────────┘
```

### 🧊 The Science

The **Peltier module (TEC)** uses electricity to create a temperature difference:
- One side gets **cold**, the other gets **hot**
- The cold side cools the heatsink **below the dew point**
- Water vapor in passing air **condenses** into droplets on the fins
- Droplets fall by **gravity** into the container below

---

## 🔩 Components

| Component | Role |
|-----------|------|
| **Peltier Module (TEC1-12706)** | Creates cold & hot sides via thermoelectric effect |
| **Aluminum Heatsink × 2** | Cold: condenses water · Hot: dissipates heat |
| **Cooling Fan** | Pushes airflow over cold heatsink |
| **Thermal Paste** | Maximizes heat transfer between Peltier & heatsinks |
| **DC Power Wires (Red/Black)** | 12V power supply connection |
| **Metal Stand (4 legs)** | Elevates unit for water to drip into container |
| **Plastic Container** | Collects condensed water |
| **Bolts, Zip Ties & Brackets** | Mechanical assembly |

---

## 🛠️ Build Steps

**Step 1 — Peltier Setup**
Apply thermal paste on both faces of the Peltier module for maximum thermal contact.

**Step 2 — Mount Heatsinks**
Attach one heatsink to the cold side (condensation surface) and one to the hot side. Secure with bolts and metal brackets.

**Step 3 — Attach Fan**
Mount the cooling fan on the hot side heatsink to actively exhaust heat. Connect fan wires with Peltier power wires.

**Step 4 — Assemble Frame**
Mount the full assembly onto the 4-legged metal stand with enough clearance below for water to drip freely.

**Step 5 — Place Container**
Position the plastic container directly under the cold heatsink fins.

**Step 6 — Power On**
Connect to a **12V DC** power supply. Within minutes, condensation will form on the heatsink fins and begin dripping.

---

## 📊 Specifications

| Parameter | Value |
|-----------|-------|
| Operating Voltage | 12V DC |
| Peltier Module | TEC1-12706 |
| Condensation Method | Dew Point via Thermoelectric Cooling |
| Water Output | Varies with ambient humidity & temperature |
| Coding Required | None |

---

## ✅ Results

> After powering the device, **visible water droplets** formed on the heatsink fins within minutes. Droplets accumulated and dripped into the collection container — confirming successful **moisture extraction from ambient air**.

---

## 🌍 Real-World Applications

- 🏜️ Water harvesting in dry/arid regions
- 🏕️ Off-grid and survival water generation
- 🌱 Small-scale irrigation in remote areas
- 💡 Proof-of-concept for large-scale AWG systems
- 🎓 Educational demonstration of thermoelectric effects

---

## 🚀 Future Improvements

- [ ] Add **DHT11/DHT22** humidity & temperature sensor with LCD display
- [ ] Use a **larger Peltier module** for increased water output
- [ ] Integrate a **solar panel** for fully off-grid operation
- [ ] Add **water level sensor** with LED indicator
- [ ] Design a **3D-printed enclosure**

---

## 📁 Repository Structure

```
atmospheric-water-generator/
├── images/
│   ├── Img_1.jpg       # Front view — condensation on fins
│   ├── Img_2.jpg       # Side view — full assembly with fan
│   └── Img_3.jpg       # Back view — water collected
└── README.md
```

---

## 📚 References

- [Thermoelectric / Peltier Effect — Wikipedia](https://en.wikipedia.org/wiki/Thermoelectric_effect)
- [Atmospheric Water Generation — Wikipedia](https://en.wikipedia.org/wiki/Atmospheric_water_generator)
- [Dew Point — Wikipedia](https://en.wikipedia.org/wiki/Dew_point)

---

<div align="center">

## 👤 Author

**Huda Usman**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hudausman010)

*"Turning air into water — one electron at a time."*

---

⭐ **If you found this project interesting, please give it a star!** ⭐

</div>
