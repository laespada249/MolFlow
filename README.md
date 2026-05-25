# MolFlow ⚛️

An interactive, 3D molecular dynamics and chemoinformatics simulator built with Python and VPython. Designed to visualize and compute gas filtration efficiency across customizable porous membranes in real time.

## 🚀 Overview

**MolFlow** bridges computational chemistry and software engineering. It provides a visual CAD-like sandbox where users can design their own atomic membrane structures and simulate fluid/gas dynamics under different chemical scenarios. 

*Note: This project is fully vibecoded, so some physics implementations might be unstable or simplified compared to heavy industrial scientific software, but it serves as an excellent interactive sandbox!*

### Key Features
* 🎮 **Interactive 3D Grid Editor:** Toggle Edit Mode to manually remove filter atoms and sculpt precision pores on the fly using mouse clicks.
* ↩️ **Time-Travel Mechanics:** Built-in object-oriented Undo/Redo stack engine for seamless structure modification.
* 🧪 **Dynamic Chemical Scenarios:** Instantly switch between multiple gas mixtures with variable particle mass and injection speeds (Air vs Smoke, Hydrogen extraction, and Isotope filtration).
* 🎛️ **Segmented Column UI:** Clean, structured layout grouping Core Controls, Membrane Geometry, Thermodynamics, and Injectors into distinct visual compartments.
* 📈 **Real-Time Telemetry & Kinetics Graph:** Follow a luxury dark-theme dashboard tracking real-time data alongside a live-updating plot of filtration efficiency vs. throughput capacity.
* 🌡️ **Thermodynamics Control:** Adjust system temperature (0 K to 600 K) via sliders to inject true Brownian thermal chaos, making lightweight particles bounce and zig-zag realistically based on their mass.

---

## 🧪 Simulation Modes

1. **Air Purification (Smoke vs N₂):** Standard mechanical filtration. Large, heavy soot particles are easily blocked by generic pore boundaries, while fast, microscopic Nitrogen molecules pass freely.
2. **Hydrogen Extraction (H₂ vs CH₄):** A high-speed extraction scenario. Separates ultra-lightweight Hydrogen from medium-sized Methane molecules. Turning up the temperature causes Hydrogen to behave like chaotic quantum-like flashes.
3. **Isotope Separation:** A high-precision chemical challenge mimicking uranium enrichment. Particles differ by mere fractions of a nanometer and atomic mass, requiring pixel-perfect atomic placement.

---

## 🛠️ Tech Stack & Architecture

* **Language:** Python 3
* **Graphics Core:** VPython (WebGL-based real-time 3D rendering canvas and plotting graph widgets)
* **UI Layer:** HTML/CSS injected via `wtext` widgets to support a column layout and responsive dark-theme design.
* **Under the Hood:** Custom spring-elastic collision physics, algorithmic Brownian random-walk motion scaled by particle mass and Kelvin temperature, and stack-based memory management.

---

## 💻 How to Run Locally

1. Install the required dependencies using Anaconda or pip:
   ```bash
   pip install vpython
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `molflow.ipynb` and run the simulation cell (`Shift + Enter`).
