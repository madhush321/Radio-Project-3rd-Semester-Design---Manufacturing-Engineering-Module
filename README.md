# Custom FM Radio Receiver 📻

## Overview
This repository contains the complete hardware design files, schematics, and PCB layouts for a functional FM radio receiver prototype. The system is engineered around the **RDA5807FP** single-chip broadcast FM stereo radio tuner and the **TDA2822** dual low-voltage power amplifier.

This prototype was designed and manufactured as the core project for the 3rd-semester module, *Design Principles and Manufacturing Technologies*, at the Department of Electrical and Electronic Engineering, University of Peradeniya.

## Key Features
* **Digital FM Tuning:** Utilizes the RDA5807FP IC for low-noise, high-fidelity frequency tuning.
* **Audio Amplification:** Integrated TDA2822 amplifier circuit to drive audio speakers directly from the board.
* **Custom 3D Footprints:** Includes custom-built 3D component models and footprints specifically designed for the RDA5807FP chip and audio speakers to ensure an accurate physical layout.
* **Manufacturable Design:** Fully routed PCB layout ready for fabrication.

## Software & Tools Used
* **Autodesk Fusion:** Utilized for end-to-end hardware design, including:
  * Schematic capture
  * 3D component modeling
  * PCB layout and routing

## Core Hardware Components
* **RDA5807FP** (FM Tuner IC)
* **TDA2822** (Audio Amplifier IC)
* Audio Speakers
* Assorted passive components (Capacitors, Resistors, Inductors) as specified in the schematic.

## Repository Structure
* `/Schematics` - Source schematics and exported PDF diagrams.
* `/PCB_Layout` - Gerber files, drill files, and Fusion board files ready for manufacturing.
* `/3D_Models` - Custom STEP files for components designed from scratch.
* `/Documentation` - Bill of Materials (BOM) and relevant project observation notes.

## Author
**B.M.G. Indunil Madhusanka Wijerathna**  
*Undergraduate, Electrical and Electronic Engineering*  
*University of Peradeniya (Batch E/22)*
