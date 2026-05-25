# MolFlow 

An interactive, 3D molecular dynamics and chemoinformatics simulator built with Python and VPython. Designed to visualize and compute gas filtration efficiency across customizable porous membranes in real time.

## 🚀 Overview

**MolFlow** bridges computational chemistry and software engineering. It provides a visual CAD-like sandbox where users can design their own atomic membrane structures and simulate fluid/gas dynamics under different chemical scenarios. Also this thing is vibecoded so it might be unstable and unrealistic.

### Key Features
* 🎮 **Interactive 3D Grid Editor:** Turn on Edit Mode to manually remove filter atoms and sculpt precision pores using mouse clicks.
* ↩️ **Time-Travel Mechanics:** Built-in Undo/Redo stack engine for seamless structure modification.
* 🔋 **Dynamic Chemical Scenarios:** Instantly switch between multiple realistic chemical mixtures (Air vs Smoke, Hydrogen separation, and Isotope filtration).
* 📈 **Real-Time Analytics:** Live telemetry tracking filtration efficiency and throughput capacity percentages on a clean control panel.
* 🎛️ **Geometric Sliders:** Dynamically resize the filter grid boundaries on the fly with responsive VPython sliders.

---

## 🧪 Simulation Modes

1. **Air Purification (Smoke vs N₂):** Simulates standard mechanical filtration. Large soot particles are easily blocked by generic pore sizes, while fast, microscopic Nitrogen molecules pass freely.
2. **Hydrogen Extraction (H₂ vs CH₄):** A high-speed scenario separating lightweight Hydrogen from medium-sized Methane molecules. Requires precise pore engineering.
3. **Isotope Separation:** A hardcore chemical challenge mimicking uranium enrichment. Particles differ by mere fractions of a nanometer, requiring pixel-perfect atomic placement.

---

## 🛠️ Tech Stack & Architecture

* **Language:** Python 3
* **Graphics Core:** VPython (WebGL-based real-time 3D rendering canvas)
* **Under the Hood:** Custom spring-elastic collision physics, algorithmic boundary adaptation for particle spawning, and object-oriented stack memory for state restoration.

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
