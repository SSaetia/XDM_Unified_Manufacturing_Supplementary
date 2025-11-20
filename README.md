# Supplementary Data for XDM Framework

This repository contains the raw data, simulation reports, and fabrication files supporting the research article:
**"XDM: A Unified Multi-Process Manufacturing Framework for Generative Manufacturing"**

## 📂 Repository Structure

### 1. Simulation (`/01_simulation_camera_mounting`)
Finite Element Analysis (FEA) reports comparing the monolithic FDM design vs. the XDM multi-material design (Figure 3 in manuscript).
- **Formats:** HTML reports exported from Fusion 360.

### 2. Fabrication Process (`/02_linkage_fabrication_gcode`)
The G-code file generated for the XDM Mechanical Linkage, demonstrating the multi-process printing sequence.
- **Machine:** Custom XDM Platform.
- **Processes:** FDM extrusion, Gripper insert, DIW dispensing.

### 3. Mechanical Testing (`/03_linkage_mechanical_testing_tensile`)
Raw data from uniaxial tensile testing of mechanical linkages (Figure 8 in manuscript).
- **Format:** Individual `.csv` files for each specimen.
- **Metadata:** See `metadata.csv` for specimen dimensions (Area, Gauge Length) and test parameters.
- **Images:** Origin and Fractured specimen photos are provided in the `images/` directory.

**Supatpromrungsee Saetia**
*Department of Mechanical Engineering, Chulalongkorn University*