# 🦅 Morphing Wing Prototype — Bioinspired Adaptive UAV Wing Design

This project explores the design, prototyping, and refinement of a **morphing UAV wing** inspired by **biological systems and aerodynamic optimization principles**. The wing was designed to perform two key types of morphing:

- **Flap Morphing (Up/Down)**  
- **Variable Aerofoil Thickness Morphing**

Both were implemented using a **servo-driven rack and pinion mechanism**, allowing dynamic adaptation of the wing shape during flight simulation scenarios. Morphing wings offer major advantages over traditional fixed-wing designs, such as:

- Improved **lift-to-drag ratio** under changing flight conditions  
- Enhanced **fuel efficiency** during cruise  
- Greater **maneuverability and stall delay**  

Initial prototyping was done using **TPU 95A filament** via 3D printing, chosen for its flexibility and elastic properties that allow smooth deformation. However, this version revealed two major insights:

1. **Structural Weakness** — Fully TPU-printed wings lacked stiffness and could not sustain aerodynamic loads.  
2. **Low ROI on Thickness Morphing** — The variable thickness mechanism added mechanical complexity with minimal aerodynamic gain.

---

## 🔬 Bioinspired Redesign: From Nature to Wing

While researching alternative aerodynamic enhancements, the project pivoted towards **biomimicry**. The redesigned prototype includes:

### 🐋 Leading Edge Tubercles  
Inspired by the **humpback whale**, these "bumps" on the wing's leading edge disrupt airflow to delay stall and maintain lift at higher angles of attack. Benefits observed in research include:

- **+8% increase in lift**  
- **+40% increase in stall angle**  
- **−32% drag reduction** in post-stall conditions  

### 🏌️‍♂️ Golf Ball Dimples  
The wing surface was textured with **micro-dimples**, mimicking the boundary layer control effect of a golf ball. These dimples:

- Create a **turbulent boundary layer** that stays attached longer  
- **Reduce pressure drag by 2–4%**  
- Improve aerodynamic efficiency in transitional flight regimes  

---

## 🧪 Material Redesign: Dual-Material 3D Print Strategy

To address the structural issues of the original prototype, the **revised wing design** incorporates **two distinct materials**:

- **PLA** for the non-morphing sections (e.g., structural core, mounting base)  
  - Offers increased rigidity and structural integrity  
  - Reduces overall weight while maintaining strength  
- **TPU 95A** for the morphing sections (e.g., flaps and flexible surfaces)  
  - Retains the necessary flexibility for active morphing  
  - Ensures smooth servo-actuated deformation  

This hybrid material approach is aimed at maintaining a balance between **flexibility and load-bearing capability**—critical for practical UAV applications.

---

## ⚠️ Performance Data Disclaimer

All aerodynamic benefits and performance metrics mentioned above (lift gain, drag reduction, stall angle improvements, etc.) are **based on publicly available research and similar bioinspired morphing wing projects** conducted by other researchers or organizations. These values are **not the result of direct testing or simulations of this specific prototype** and are provided as **theoretical benchmarks** for context.

---

## 🚧 Current Status

- ✅ **Initial TPU prototype completed and tested**  
- ✅ **Dual-material redesign completed (PLA + TPU split architecture)**  
- ⚠️ **Redesigned bioinspired prototype modeled, not yet printed**  
- 🧪 **CFD simulations pending** to validate aerodynamic performance (L/D ratio, stall characteristics, drag profile)  
- 🔩 **Material integration strategy being finalized** for multi-material 3D printing workflow

---

## 🚀 Vision

This project aims to contribute toward **next-generation UAV design**, where **adaptive, passive, and bioinspired morphing mechanisms** can enhance flight performance without relying on complex actuation systems. The goal is to enable lighter, more efficient, and more agile UAVs suitable for both civilian and defense applications.

---

## 📁 Folder Structure

