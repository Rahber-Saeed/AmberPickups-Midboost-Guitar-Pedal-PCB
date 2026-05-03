# AmberPickups-Midboost-Guitar-Pedal-PCB
Open-source hardware design for a guitar mid-boost effects pedal. Built around the TL062 low-power JFET-input dual op-amp for clear, high-impedance audio processing. Perfect for lead guitarists looking to cut through the mix. Includes schematics, PCB layout, BOM, and 3D render.
# AmberPickups Midboost Ver. 1 – Guitar Effects PCB

![EasyEDA](https://img.shields.io/badge/Designed_in-EasyEDA-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the complete hardware design files for the **AmberPickups Midboost Ver. 1**, a classic mid-boost guitar effects pedal PCB. This circuit is designed to boost the mid-range frequencies of your guitar signal, allowing you to cut through a dense band mix or add punch to your lead tones.

![3D Render](images/3d_render.png) <!-- Remember to place your 3D render and PCB images in an 'images/' folder -->

## ✨ Project Overview
------------------------------------------
<img width="650" height="582" alt="Schematic_TL062P_2026-04-13" src="https://github.com/user-attachments/assets/f1026c83-f99d-4e98-9e7b-9e71d34b15d0" />

-----------------------------------------------
<img width="617" height="663" alt="3D_TOP_FIGURE_PCB_TL062P" src="https://github.com/user-attachments/assets/1864a1b9-51db-4e14-801e-53214cf4372e" />

------------------------------------------------
<img width="678" height="725" alt="3D_BACK_FIGURE_PCB_TL062P" src="https://github.com/user-attachments/assets/5bdfd02b-35b0-4af9-8fa8-c9ac3f8164f4" />

------------------------------------------
<img width="550" height="562" alt="2D_FIGURE__PCB_TL062P" src="https://github.com/user-attachments/assets/66a2628e-bd65-462c-b606-4fc7af1f85f9" />

------------------------------------------------
This is an analog, op-amp-based active EQ/boost circuit. It takes your standard 9V power supply, processes the high-impedance guitar signal, and outputs a boosted, sculpted midrange tone.

*   **Core IC:** **TL062CP** – A low-power, JFET-input dual operational amplifier renowned for its high input impedance and low noise floor.
*   **Circuit Topology:**
    *   **Active Filter/Boost Stage (U1.1):** The primary gain and EQ shaping stage.
    *   **Output Buffer Stage (U1.2):** Ensures your guitar signal maintains its integrity and high impedance before hitting the output jack.
*   **Protection:** Includes a **1N914** reverse-polarity protection diode (D2) to safeguard the circuit from accidental wrong power connections.

## 📂 Repository Structure
```text
/
├── images/                               # PCB renders and screenshots
├── Schematic_TL062P_2026-04-13.pdf       # Full circuit schematics
├── PCB_PCB_TL062P_2026-04-13.pdf         # PCB layout visual
├── BOM_TL062P_2026-04-13.csv             # Bill of Materials
└── PickAndPlace_PCB_TL062P_2026-04-13.csv # Pick & Place coordinates
