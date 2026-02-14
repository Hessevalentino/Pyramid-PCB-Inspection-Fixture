# Pyramid PCB Inspection Fixture

[![License: CERN-OHL-P-2.0](https://img.shields.io/badge/License-CERN--OHL--P--2.0-blue.svg)](https://spdx.org/licenses/CERN-OHL-P-2.0.html)
[![Open Hardware](https://img.shields.io/badge/Hardware-Open-orange.svg)](https://www.oshwa.org/definition/)
[![3D Printable](https://img.shields.io/badge/3D-Printable-green.svg)](https://www.thingiverse.com/)
[![ESD Safe](https://img.shields.io/badge/ESD-Safe-yellow.svg)](https://en.wikipedia.org/wiki/Electrostatic_discharge)
[![Automotive](https://img.shields.io/badge/Industry-Automotive-red.svg)](https://en.wikipedia.org/wiki/Automotive_industry)
[![Made with Inventor](https://img.shields.io/badge/Made%20with-Autodesk%20Inventor-0696D7.svg)](https://www.autodesk.com/products/inventor/)

---

### Description

The Pyramid PCB Inspection Fixture is a specialized tool for PCB (Printed Circuit Board) analysis under microscope. This pyramid-shaped fixture was designed for the automotive industry and enables precise positioning and stabilization of PCBs during microscopic inspection.

### Author and Origin

**Valentino Hesse**

This project originated as an original invention during professional work. The design was successfully implemented in an industrial environment and is now released as an open hardware project for the technical community.

### Manufacturing Specifications

- **Material:** ESD PET (Electrostatic Discharge dissipative polyethylene terephthalate)
- **Manufacturing Technology:** Additive manufacturing (3D printing)
- **Industry Sector:** Automotive

<img width="1108" height="782" alt="image" src="https://github.com/user-attachments/assets/7f60f68c-e886-4691-af0a-8c08a72c8ced" />


#### Required ESD Material Parameters

| Parameter | Value | Standard |
|-----------|-------|----------|
| Surface Resistivity | 10⁶ - 10⁹ Ω/sq | IEC 61340-5-1 |
| Volume Resistivity | 10⁴ - 10¹¹ Ω·cm | IEC 61340-5-1 |
| Charge Decay Time | < 2 s | IEC 61340-5-1 |
| Printing Temperature | 230 - 250 °C | - |
| Bed Temperature | 70 - 85 °C | - |
| Density | 1.27 - 1.29 g/cm³ | - |

**Note:** Material must comply with IEC 61340-5-1 standard for protection of electronic components against electrostatic discharge (ESD). Recommended filament materials: 3DXTech ESD-PETG, Protopasta Conductive PLA, or equivalent with ESD certification.

### Repository Contents

- **`pyramid.ipt`** - Autodesk Inventor Part file (source 3D model for modifications)
- **`pyramid.idw`** - Autodesk Inventor Drawing file (technical drawing with dimensions)
- **`pyramid.stl`** - STL file for additive manufacturing
- **`pyramid.pdf`** - PDF documentation and technical drawing
- **`LICENSE`** - Full text of CERN-OHL-P v2 license

<img width="338" height="791" alt="image" src="https://github.com/user-attachments/assets/541fba48-d1d3-4bc1-9168-c8fef737f196" />


### Usage

1. Download the `pyramid.stl` file
2. Print on a 3D printer using ESD PET material
3. Use as a fixture for PCB during microscopic analysis

### Design Modifications

To modify the design:
1. Open the `pyramid.ipt` file in Autodesk Inventor
2. Make the required changes
3. Export a new STL file for manufacturing

### License

This project is licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P v2)**.

**Terms of Use:**
- Free use, copying, modification, and distribution
- Commercial use permitted
- Manufacturing and sale of physical products permitted
- Attribution to author required (Valentino Hesse)
- Provision of license reference required

More information in the [LICENSE](LICENSE) file.

---

## Contributing

Contributions are welcome. If you improve the design, please share your modifications back to the community.

---

## Contact

**Valentino Hesse**

For questions or commercial inquiries, please open an issue in this repository.

---

**Copyright © 2025 Valentino Hesse**
Licensed under CERN-OHL-P v2

