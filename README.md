# EV-Battery-Thermal-Simulation

## Project Overview
This repository focuses on the thermal management and cooling optimization of Electric Vehicle (EV) battery packs. The goal is to design an efficient liquid cooling plate geometry using SolidWorks, simulate transient heat dissipation profiles using ANSYS Fluent, and utilize Python for mathematical modeling and parametric data analysis.

Special emphasis is placed on exploring advanced material properties—including high-conductivity thermal interfaces and zinc-aluminum (ZA-27) alloy parameters—to enhance heat transfer efficiency under high-discharge conditions.

## Project Architecture
- `/cad` : SolidWorks geometric models of the battery cells and cooling channel plates.
- `/ansys` : Computational Fluid Dynamics (CFD) setups, mesh metrics, and boundary conditions.
- `/src` : Python scripts for theoretical thermal calculations and data visualization.
- `/docs` : Research logs, material property datasheets, and analytical references.

## Core Technical Objectives
1. **Mathematical Modeling (Python):** Develop a 1D/2D transient heat generation model for a lithium-ion cell based on internal resistance and discharge rates.
2. **CAD Design (SolidWorks):** Model a serpentine/parallel channel cooling plate optimized for uniform flow distribution.
3. **CFD Simulation (ANSYS Fluent):** Analyze temperature uniformity, pressure drop, and heat transfer coefficients across the cooling plate using varying coolant flow rates.
4. **Data Optimization:** Compare the thermal mitigation capabilities of traditional aluminum vs. alternative high-strength alloys under peak thermal loads.

## Current Progress & Roadmap
- [x] Repository initialization and structural planning.
- [ ] Coding the baseline analytical heat generation script (Python).
- [ ] Generating the preliminary 3D cooling plate geometry (SolidWorks).
- [ ] Execution of steady-state CFD thermal simulations (ANSYS).

## Prerequisites & Tools
- Python 3.x (Libraries: NumPy, Matplotlib, SciPy)
- SolidWorks
- ANSYS Fluent
