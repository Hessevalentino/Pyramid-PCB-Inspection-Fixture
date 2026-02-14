# Changelog

All notable changes to the Pyramid PCB Inspection Fixture project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.0] - 2026-02-14

### Added
- **pyramid-NOesd.stl** - Non-ESD version of the fixture for general use cases where ESD protection is not required
- **NOTICE** file - Copyright and license information as required by CERN-OHL-P v2
- **CHANGELOG.md** - This file, documenting all modifications to the design
- **BOM.md** - Bill of Materials with certified ESD materials and specifications
- **TESTING.md** - Testing protocols for ESD compliance and quality assurance
- Enhanced README.md with version information, traceability, and complete documentation

### Changed
- **pyramid.stl** - Updated 3D model with improved geometry for better PCB stability
- Updated documentation to meet automotive Class 3 standards (IPC-A-610)
- Enhanced ESD material specifications with detailed testing requirements

### Technical Details
- Modified pyramid geometry for enhanced PCB contact stability
- Optimized wall thickness for improved structural integrity during microscopic inspection
- Refined base dimensions for better microscope stage compatibility

### Compliance
- Full compliance with CERN-OHL-P v2 license requirements
- Meets IEC 61340-5-1 ESD protection standards
- Designed for automotive Class 3 PCB inspection per IPC-A-610

---

## [1.0] - 2025-01-XX

### Added
- Initial release of Pyramid PCB Inspection Fixture
- **pyramid.ipt** - Autodesk Inventor source file
- **pyramid.idw** - Technical drawing with dimensions
- **pyramid.stl** - STL file for 3D printing with ESD material
- **pyramid.pdf** - PDF documentation
- **LICENSE** - CERN-OHL-P v2 license
- **README.md** - Project documentation

### Technical Specifications
- Material: ESD PET (Electrostatic Discharge dissipative)
- Surface Resistivity: 10⁶ - 10⁹ Ω/sq
- Volume Resistivity: 10⁴ - 10¹¹ Ω·cm
- Compliance: IEC 61340-5-1

### Origin
- Original invention developed during professional work in automotive industry
- Successfully implemented in industrial PCB inspection environment
- Released as open hardware project for technical community

---

## Version History Summary

| Version | Date       | Description                                    | Author          |
|---------|------------|------------------------------------------------|-----------------|
| 2.0     | 2026-02-14 | Updated model, added non-ESD version, enhanced documentation | Valentino Hesse |
| 1.0     | 2025-01-XX | Initial public release                         | Valentino Hesse |

---

## Modification Guidelines

When modifying this design, please:

1. **Document your changes** in this CHANGELOG.md file
2. **Update the version number** following semantic versioning
3. **Mark modifications** clearly in your documentation
4. **Test thoroughly** especially for ESD compliance if applicable
5. **Share improvements** back to the community (encouraged but not required under CERN-OHL-P)

### Modification Template

```markdown
## [X.Y.Z] - YYYY-MM-DD

### Added
- List new features or files

### Changed
- List modifications to existing design

### Fixed
- List bug fixes or corrections

### Removed
- List removed features or files

### Technical Details
- Describe technical changes in detail

### Compliance
- Note any compliance or certification impacts
```

---

## Notes

- All dates in ISO 8601 format (YYYY-MM-DD)
- Version numbers follow semantic versioning (MAJOR.MINOR.PATCH)
- Changes are listed in reverse chronological order (newest first)
- Each version includes author attribution as required by CERN-OHL-P v2

---

**Maintained by:** Valentino Hesse  
**Repository:** https://github.com/Hessevalentino/Pyramid-PCB-Inspection-Fixture  
**License:** CERN-OHL-P v2

