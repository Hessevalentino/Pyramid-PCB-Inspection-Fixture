# Pyramid PCB Inspection Fixture

**Version 2.0** | **Last Updated: 2026-02-14** | **Automotive Class 3 Compliant**

[![License: CERN-OHL-P-2.0](https://img.shields.io/badge/License-CERN--OHL--P--2.0-blue.svg)](https://spdx.org/licenses/CERN-OHL-P-2.0.html)
[![Open Hardware](https://img.shields.io/badge/Hardware-Open-orange.svg)](https://www.oshwa.org/definition/)
[![3D Printable](https://img.shields.io/badge/3D-Printable-green.svg)](https://www.thingiverse.com/)
[![ESD Safe](https://img.shields.io/badge/ESD-Safe-yellow.svg)](https://en.wikipedia.org/wiki/Electrostatic_discharge)
[![Automotive](https://img.shields.io/badge/Industry-Automotive-red.svg)](https://en.wikipedia.org/wiki/Automotive_industry)
[![Made with Inventor](https://img.shields.io/badge/Made%20with-Autodesk%20Inventor-0696D7.svg)](https://www.autodesk.com/products/inventor/)
[![IPC Class 3](https://img.shields.io/badge/IPC-Class%203-brightgreen.svg)](https://www.ipc.org/)

---

## Table of Contents

- [Description](#description)
- [Version Information](#version-information)
- [Author and Origin](#author-and-origin)
- [Manufacturing Specifications](#manufacturing-specifications)
- [Repository Contents](#repository-contents)
- [Documentation](#documentation)
- [Usage](#usage)
- [Design Modifications](#design-modifications)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

---

## Description

The Pyramid PCB Inspection Fixture is a specialized tool for PCB (Printed Circuit Board) analysis under microscope. This pyramid-shaped fixture was designed for the automotive industry and enables precise positioning and stabilization of PCBs during microscopic inspection.

---

## Version Information

| Parameter | Value |
|-----------|-------|
| **Current Version** | 2.0 |
| **Release Date** | 2026-02-14 |
| **Design Status** | Production Ready |
| **Compliance** | IPC-A-610 Class 3, IEC 61340-5-1 |
| **SPDX License ID** | CERN-OHL-P-2.0 |

**What's New in Version 2.0:**
- Added non-ESD version (`pyramid-NOesd.stl`) for general applications
- Enhanced documentation with professional testing protocols
- Complete Bill of Materials with certified ESD materials
- Comprehensive quality assurance procedures
- Full traceability and compliance documentation

See [CHANGELOG.md](CHANGELOG.md) for complete version history.

---

## Author and Origin

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
| Surface Resistivity | 10⁶ - 10⁹ Ω | IEC 61340-5-1 |
| Volume Resistivity | 10⁴ - 10¹¹ Ω·cm2 | IEC 61340-5-1 |
| Charge Decay Time | < 2 s | IEC 61340-5-1 |
| Printing Temperature | 230 - 250 °C | - |
| Bed Temperature | 70 - 85 °C | - |
| Density | 1.27 - 1.29 g/cm³ | - |

**Note:** Material must comply with IEC 61340-5-1 standard for protection of electronic components against electrostatic discharge (ESD). Recommended filament materials: 3DXTech ESD-PETG, Protopasta Conductive PLA, or equivalent with ESD certification.

For complete material specifications and approved suppliers, see [BOM.md](BOM.md).

---

## Repository Contents

### Design Files

- **`pyramid.ipt`** - Autodesk Inventor Part file (source 3D model for modifications)
- **`pyramid.idw`** - Autodesk Inventor Drawing file (technical drawing with dimensions)
- **`pyramid.pdf`** - PDF documentation and technical drawing

### Manufacturing Files

- **`pyramid.stl`** - STL file for 3D printing with **ESD-safe material** (primary version)
- **`pyramid-NOesd.stl`** - STL file for 3D printing with **standard material** (non-ESD version for general use)

### Documentation

- **`README.md`** - This file, project overview and quick start guide
- **`LICENSE`** - Full text of CERN-OHL-P v2 license
- **`NOTICE`** - Copyright and license notices (required by CERN-OHL-P v2)
- **`CHANGELOG.md`** - Version history and modification log
- **`BOM.md`** - Bill of Materials with certified ESD materials and suppliers
- **`TESTING.md`** - Quality assurance and testing protocols for Class 3 compliance

**Which version should I use?**
- **Use `pyramid.stl` (ESD version)** for automotive, aerospace, medical, or any application involving sensitive electronics
- **Use `pyramid-NOesd.stl` (non-ESD version)** for general PCB inspection where ESD protection is not required

<img width="338" height="791" alt="image" src="https://github.com/user-attachments/assets/541fba48-d1d3-4bc1-9168-c8fef737f196" />

---

## Documentation

This project includes comprehensive professional documentation:

| Document | Purpose | Audience |
|----------|---------|----------|
| [README.md](README.md) | Quick start and overview | All users |
| [NOTICE](NOTICE) | Copyright and license information | All users (required) |
| [LICENSE](LICENSE) | Full CERN-OHL-P v2 license text | All users |
| [CHANGELOG.md](CHANGELOG.md) | Version history and modifications | Developers, QA |
| [BOM.md](BOM.md) | Materials, suppliers, specifications | Manufacturing, Procurement |
| [TESTING.md](TESTING.md) | Quality assurance protocols | QA, Manufacturing |
| [pyramid.pdf](pyramid.pdf) | Technical drawings and dimensions | Manufacturing, Engineering |

---

## Usage

### Quick Start (ESD Version)

1. Download the **`pyramid.stl`** file
2. Print on a 3D printer using **ESD PET material** (see [BOM.md](BOM.md) for approved materials)
3. **Test ESD properties** after printing (see [TESTING.md](TESTING.md))
4. Use as a fixture for PCB during microscopic analysis

### Quick Start (Non-ESD Version)

1. Download the **`pyramid-NOesd.stl`** file
2. Print on a 3D printer using standard PET/PETG material
3. Verify dimensions (see [TESTING.md](TESTING.md))
4. Use for general PCB inspection (non-sensitive electronics only)

<img width="1073" height="599" alt="image" src="https://github.com/user-attachments/assets/26e5fd2b-e646-40a4-898c-ed8ceea7ce9d" />
<img width="1080" height="594" alt="image" src="https://github.com/user-attachments/assets/1c3afd79-113a-42d1-a879-817b76296173" />

---

## Design Modifications

To modify the design:

1. **Open the source file:** `pyramid.ipt` in Autodesk Inventor
2. **Make your changes** to the 3D model
3. **Update the drawing:** Modify `pyramid.idw` if dimensions changed
4. **Export new STL:** File → Export → CAD Format → STL
5. **Document changes:** Update [CHANGELOG.md](CHANGELOG.md) with your modifications
6. **Test the new design:** Follow protocols in [TESTING.md](TESTING.md)
7. **Share back:** Consider contributing improvements to the community

**Important:** When modifying this design, you must comply with CERN-OHL-P v2 requirements:
- Retain copyright notices
- Document your modifications in CHANGELOG.md
- Provide attribution to original author (Valentino Hesse)
- Include license reference

---

## License

This project is licensed under the **CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P v2)**.

**SPDX License Identifier:** `CERN-OHL-P-2.0`

### Terms of Use

✅ **You are free to:**
- Use, study, modify, and distribute this hardware design
- Make products based on this design
- Use this design for commercial purposes
- Sell products manufactured from this design

📋 **Under these conditions:**
- You must retain copyright and license notices (see [NOTICE](NOTICE))
- You must provide attribution to the original author (Valentino Hesse)
- You must include a copy of or reference to the CERN-OHL-P v2 license
- Modified versions must be clearly marked and documented in CHANGELOG.md

### Documentation

- Full license text: [LICENSE](LICENSE) file
- Copyright notice: [NOTICE](NOTICE) file
- License URL: https://ohwr.org/cern_ohl_p_v2.txt
- SPDX: https://spdx.org/licenses/CERN-OHL-P-2.0.html

---

## Quality & Compliance

This design meets the following standards:

| Standard | Description | Compliance |
|----------|-------------|------------|
| **IPC-A-610 Class 3** | High-reliability electronic products | ✅ Design compliant |
| **IEC 61340-5-1** | ESD protection requirements | ✅ Material specified |
| **CERN-OHL-P v2** | Open hardware license | ✅ Full compliance |
| **ISO 9001** | Quality management (recommended for manufacturing) | 📋 Documented |
| **IATF 16949** | Automotive quality (recommended) | 📋 Automotive-ready |

See [TESTING.md](TESTING.md) for validation procedures.

---

## Contributing

Contributions are welcome! If you improve the design, please:

1. **Fork** this repository
2. **Make your changes** following the modification guidelines above
3. **Document** your changes in CHANGELOG.md
4. **Test** your modifications (see TESTING.md)
5. **Submit a pull request** with clear description of improvements

We encourage sharing improvements back to the community, though it's not required under CERN-OHL-P v2.

### Contribution Ideas

- Variations for different PCB sizes
- Adaptations for specific microscope models
- Alternative materials testing
- Improved manufacturing processes
- Translations of documentation

---

## Support & Contact

**Author:** Valentino Hesse
**Repository:** https://github.com/Hessevalentino/Pyramid-PCB-Inspection-Fixture
**License:** CERN-OHL-P v2

### Getting Help

- 🐛 **Bug reports:** Open an issue with "Bug:" prefix
- 💡 **Feature requests:** Open an issue with "Feature:" prefix
- 📖 **Documentation:** Open an issue with "Docs:" prefix
- 💬 **Questions:** Open an issue with "Question:" prefix
- 🏢 **Commercial inquiries:** Open an issue or contact via GitHub

---

## Traceability Information

| Field | Value |
|-------|-------|
| **Project Name** | Pyramid PCB Inspection Fixture |
| **Version** | 2.0 |
| **Release Date** | 2026-02-14 |
| **Author** | Valentino Hesse |
| **License** | CERN-OHL-P-2.0 |
| **Repository** | https://github.com/Hessevalentino/Pyramid-PCB-Inspection-Fixture |
| **Industry** | Automotive |
| **Application** | PCB Microscopic Inspection |
| **Compliance** | IPC-A-610 Class 3, IEC 61340-5-1 |

---

**Copyright © 2025-2026 Valentino Hesse**
Licensed under CERN Open Hardware Licence Version 2 - Permissive

**Made with ❤️ for the open hardware community**

