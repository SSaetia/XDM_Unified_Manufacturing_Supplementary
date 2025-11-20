# Supplementary Data for XDM Framework

This repository contains the raw data, simulation reports, and fabrication files supporting the research article:
**"XDM: A Unified Multi-Process Manufacturing Framework for Generative Manufacturing"**

## 📂 Repository Structure

### 1. (Figure 3) Simulation (`/01_simulation_camera_mounting`)
Finite Element Analysis (FEA) reports comparing the monolithic FDM design vs. the XDM multi-material design (Figure 3 in manuscript).
- **Formats:** HTML reports exported from Fusion 360.

### 2. Fabrication Process (`/02_linkage_fabrication_gcode`)
The full XDM fabrication process video: 
https://youtu.be/Do7YRbkYg8k?si=tqd1KRPBfQMFofAA

The G-code file generated for the XDM Mechanical Linkage, demonstrating the multi-process printing sequence.
- **Machine:** Custom XDM Platform.
- **Processes:** FDM extrusion, Gripper insert, DIW dispensing.

### 3. (Figure 8) Mechanical Testing (`/03_linkage_mechanical_testing_tensile`)
Raw data from uniaxial tensile testing of mechanical linkages (Figure 8 in manuscript).
- **Format:** Individual `.csv` files for each specimen.
- **Specimen Geometry:** Modified dogbone standard based on the provided CAD.
    - **Cross-sectional Area:** 40 mm² (10 mm width × 4 mm thickness)
    - **Gauge Length:** 50 mm
- **Images:** Origin and Fractured specimen photos are provided in the `images/` directory.

### 4. CAD Design (`/04_linkage_cad`)
The reference 3D model of the mechanical linkage used for testing.
- **File:** `linkage.step` (Standard STEP format).

**Supatpromrungsee Saetia**
*Department of Mechanical Engineering, Chulalongkorn University*
