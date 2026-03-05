<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0f1e,100:00b4d8&height=140&text=Water%20Extractor%20from%20Air&fontSize=36&fontColor=ffffff&fontAlignY=40&desc=Harvesting%20Water%20from%20Thin%20Air%20%7C%20Powered%20by%20Thermoelectrics&descAlignY=60&descSize=14&desc2=%F0%9F%8F%86%20Sustainability%20Innovation%20Award%20%E2%80%94%20STMU%202024&desc2AlignY=80&desc2Size=13&desc2Color=ffd700" width="100%"/>

<br/>

<!-- BADGES -->
![Status](https://img.shields.io/badge/Status-Working%20Prototype-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Hardware%20Project-0077b6?style=for-the-badge)
![No Code](https://img.shields.io/badge/Code-None%20Required-90e0ef?style=for-the-badge&logoColor=black)
![Voltage](https://img.shields.io/badge/Power-12V%20DC-red?style=for-the-badge)
![Peltier](https://img.shields.io/badge/Module-TEC1--12706-00b4d8?style=for-the-badge)

<br/>

> ### *"Turning air into water — one electron at a time."*
> A working **Atmospheric Water Generator** built from scratch using the Peltier thermoelectric effect —
> no code, pure physics.

<br/>

[🌊 Overview](#-overview) • [⚙️ How It Works](#️-how-it-works) • [🔩 Components](#-components) • [🛠️ Build Steps](#️-build-steps) • [📊 Results](#-results) • [🚀 Future](#-future-improvements)

</div>

---

## 🌊 Overview

This project is a **mini Atmospheric Water Generator (AWG)** that extracts moisture directly from ambient air and converts it into liquid water droplets — **no coding required**, purely electronics and thermodynamics.

It showcases the practical application of the **Peltier (thermoelectric) effect** to cool a surface below the **dew point**, causing water vapor in the air to condense and drip into a collection container.

<div align="center">

```
🌫️ Humid Air  ──►  🌀 Fan  ──►  ❄️ Cold Heatsink  ──►  💧 Droplets  ──►  🪣 Container
```

</div>

---

## 📸 Gallery

<div align="center">

<table>
  <tr>
    <td align="center" width="33%">
      <img src="images/Img_1.jpg" width="220" style="border-radius:10px"/>
      <br/><sub><b>🔍 Front View</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="images/Img_2.jpg" width="220" style="border-radius:10px"/>
      <br/><sub><b>↔️ Side View</b></sub>
    </td>
    <td align="center" width="33%">
      <img src="images/Img_3.jpg" width="220" style="border-radius:10px"/>
      <br/><sub><b>🔬 Close-up View</b></sub>
    </td>
  </tr>
</table>

> 💦 Water droplets visibly forming on the heatsink fins — **proof it works!**

</div>

---

## ⚙️ How It Works

The system exploits a fundamental property of thermoelectric modules — one face gets ice-cold, the other gets hot. When moist air flows over the cold face, it drops below the **dew point** and water vapor condenses into liquid droplets.

<br/>

<div align="center">

| Step | Component | What Happens |
|:----:|:---------:|:-------------|
| 1️⃣ | **Cooling Fan** | Blows humid ambient air across the cold heatsink |
| 2️⃣ | **Peltier Module** | Creates a cold side and a hot side via current flow |
| 3️⃣ | **Cold Heatsink** | Surface drops below dew point → moisture condenses |
| 4️⃣ | **Gravity** | Water droplets accumulate and slide down the fins |
| 5️⃣ | **Collection Container** | Catches all extracted water beneath the assembly |
| 6️⃣ | **Hot Heatsink + Paste** | Exhausts waste heat away to keep the system efficient |

</div>

---

## 🔩 Components

<div align="center">

| Component | Spec | Role |
|-----------|------|------|
| **Peltier Module** | TEC1-12706 | Creates cold & hot sides via thermoelectric effect |
| **Aluminum Heatsink × 2** | Standard fin type | Cold: condenses water · Hot: dissipates heat |
| **Cooling Fan** | 12V DC | Pushes airflow over cold heatsink surface |
| **Thermal Paste** | Standard | Maximizes heat transfer between Peltier & heatsinks |
| **DC Power Wires** | Red / Black | 12V power supply connection |
| **Metal Stand** | 4-legged | Elevates unit for water to drip into container below |
| **Plastic Container** | Any size | Collects condensed water |
| **Bolts, Zip Ties & Brackets** | — | Mechanical assembly & stability |

</div>

---

## 🛠️ Build Steps

<div align="center">

| # | Step | Details |
|:---:|:----:|:--------|
| 🔧 **1** | **Peltier Setup** | Apply thermal paste evenly on both faces for maximum heat transfer |
| 🔩 **2** | **Mount Heatsinks** | Cold side → condensation · Hot side → heat dissipation · Secure with bolts |
| 🌀 **3** | **Attach Fan** | Mount on hot side heatsink · Connect wires alongside Peltier leads |
| 🦿 **4** | **Assemble Frame** | Fix full assembly on 4-legged stand · Leave clearance below for dripping |
| 📦 **5** | **Place Container** | Position plastic container directly under cold heatsink fins |
| ⚡ **6** | **Power On** | Connect to **12V DC** · Wait a few minutes · Watch the water appear 💧 |

</div>

---

## 📊 Specifications

<div align="center">

| Parameter | Value |
|:----------|:------|
| Operating Voltage | 12V DC |
| Peltier Module | TEC1-12706 |
| Condensation Method | Dew Point via Thermoelectric Cooling |
| Water Output | Varies with ambient humidity & temperature |
| Coding Required | ❌ None |

</div>

---

## ✅ Results

<div align="center">

> 💧 After powering the device, **visible water droplets** formed on the heatsink fins within minutes.
> Droplets accumulated and dripped into the collection container — confirming successful
> **moisture extraction from ambient air**.

</div>

The output volume depends on:
- 🌡️ **Ambient temperature** — cooler air holds less moisture
- 💨 **Relative humidity** — higher humidity = more water
- ⚡ **Power stability** — consistent 12V gives best results
- ⏱️ **Run time** — longer runtime = more collection

---

## 🌍 Real-World Applications

<div align="center">

| Application | Impact |
|-------------|--------|
| 🏜️ **Arid Region Water Harvesting** | Provides drinking water where rainfall is scarce |
| 🏕️ **Off-grid & Survival Use** | Emergency water source without infrastructure |
| 🌱 **Remote Area Irrigation** | Small-scale crop watering in isolated locations |
| 💡 **AWG Proof-of-Concept** | Foundation for scaling to larger systems |
| 🎓 **Educational Demonstration** | Hands-on thermoelectric effect learning tool |

</div>

---

## 🚀 Future Improvements

- [ ] Add **DHT11/DHT22** humidity & temperature sensor with LCD display
- [ ] Use a **larger Peltier module** (TEC1-12715) for increased water output
- [ ] Integrate a **solar panel** for fully off-grid operation
- [ ] Add **water level sensor** with LED/buzzer indicator
- [ ] Design a **3D-printed enclosure** for a clean finished look
- [ ] Add **multi-stage cooling** to improve efficiency in low-humidity conditions

---

## 📁 Repository Structure

```
atmospheric-water-generator/
│
├── 📂 images/
│   ├── Img_1.jpg       # Front view — full assembly
│   ├── Img_2.jpg       # Side view — fan & heatsink
│   └── Img_3.jpg       # Close-up — condensation on fins
│
└── README.md
```

---

## 📚 References

- 🔗 [Thermoelectric / Peltier Effect — Wikipedia](https://en.wikipedia.org/wiki/Thermoelectric_effect)
- 🔗 [Atmospheric Water Generation — Wikipedia](https://en.wikipedia.org/wiki/Atmospheric_water_generator)
- 🔗 [Dew Point — Wikipedia](https://en.wikipedia.org/wiki/Dew_point)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00b4d8,100:0a0f1e&height=80&section=footer" width="100%"/>

### 🙋‍♀️ Connect with Me

Developed by **Huda Usman**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Huda%20Usman-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hudausman010)

<br/>

⭐ **If you found this project interesting, please give it a star!** ⭐

</div>
