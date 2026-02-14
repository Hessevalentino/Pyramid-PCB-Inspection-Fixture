# Bill of Materials (BOM)

## Pyramid PCB Inspection Fixture - Version 2.0

This document lists all materials and components required to manufacture the Pyramid PCB Inspection Fixture for automotive Class 3 PCB inspection applications.

---

## 1. Primary Materials

### 1.1 ESD Version (pyramid.stl)

| Item | Description | Specification | Quantity | Unit | Notes |
|------|-------------|---------------|----------|------|-------|
| 1 | ESD-Safe 3D Printing Filament | ESD PET/PETG, 1.75mm or 2.85mm | ~50g | per piece | See approved materials below |

### 1.2 Non-ESD Version (pyramid-NOesd.stl)

| Item | Description | Specification | Quantity | Unit | Notes |
|------|-------------|---------------|----------|------|-------|
| 1 | Standard 3D Printing Filament | PET/PETG, 1.75mm or 2.85mm | ~50g | per piece | For non-sensitive applications only |

---

## 2. Approved ESD Materials

The following materials have been tested and approved for automotive Class 3 ESD applications:

### 2.1 Recommended Primary Materials

| Manufacturer | Product Name | Part Number | Surface Resistivity | Certification | Availability |
|--------------|--------------|-------------|---------------------|---------------|--------------|
| 3DXTech | ESD-PETG | 3DX-ESD-PETG-175 | 10⁷ - 10⁹ Ω/sq | IEC 61340-5-1 | Global |
| Protopasta | Conductive PLA | CPL-175 | 10⁶ - 10⁸ Ω/sq | IEC 61340-5-1 | Global |
| Kimya | PETG-S ESD | KY-PETG-S-ESD | 10⁶ - 10⁹ Ω/sq | IEC 61340-5-1 | Europe |
| Polymaker | PolyLite ESD-PLA | PA03020 | 10⁶ - 10⁹ Ω/sq | IEC 61340-5-1 | Global |

### 2.2 Alternative Certified Materials

| Manufacturer | Product Name | Part Number | Surface Resistivity | Notes |
|--------------|--------------|-------------|---------------------|-------|
| Ultimaker | PLA ESD | UM-PLA-ESD | 10⁶ - 10⁹ Ω/sq | Requires specific print settings |
| ColorFabb | nGen ESD | 8719033551534 | 10⁷ - 10⁹ Ω/sq | Excellent layer adhesion |
| Fillamentum | ESD PLA | FIL-ESD-PLA | 10⁶ - 10⁸ Ω/sq | Good dimensional stability |

---

## 3. Material Requirements & Specifications

### 3.1 ESD Properties (IEC 61340-5-1 Compliance)

| Parameter | Required Value | Test Method | Acceptance Criteria |
|-----------|----------------|-------------|---------------------|
| Surface Resistivity | 10⁶ - 10⁹ Ω/sq | IEC 61340-2-3 | Must be within range |
| Volume Resistivity | 10⁴ - 10¹¹ Ω·cm | IEC 61340-2-3 | Must be within range |
| Charge Decay Time | < 2 seconds | IEC 61340-5-1 | From 1000V to 100V |
| Triboelectric Charging | < 100V | IEC 61340-2-1 | After friction test |

### 3.2 Mechanical Properties

| Parameter | Required Value | Test Method | Notes |
|-----------|----------------|-------------|-------|
| Tensile Strength | > 40 MPa | ISO 527 | Minimum for structural integrity |
| Flexural Modulus | > 2000 MPa | ISO 178 | Prevents deformation under load |
| Heat Deflection Temp | > 60°C | ISO 75 | For typical lab environments |
| Density | 1.27 - 1.29 g/cm³ | ISO 1183 | Standard for PET-based materials |

### 3.3 Print Settings

| Parameter | ESD PET/PETG | ESD PLA | Notes |
|-----------|--------------|---------|-------|
| Nozzle Temperature | 230 - 250°C | 210 - 230°C | Adjust per manufacturer specs |
| Bed Temperature | 70 - 85°C | 50 - 60°C | For optimal adhesion |
| Print Speed | 40 - 60 mm/s | 40 - 60 mm/s | Slower for better quality |
| Layer Height | 0.2 - 0.3 mm | 0.2 - 0.3 mm | Balance quality/speed |
| Infill | 20 - 30% | 20 - 30% | Sufficient for application |
| Wall Thickness | 3 - 4 perimeters | 3 - 4 perimeters | For structural strength |

---

## 4. Quality Control Materials

### 4.1 Testing Equipment (Recommended)

| Item | Description | Purpose | Required |
|------|-------------|---------|----------|
| Surface Resistance Meter | IEC 61340-2-3 compliant | Verify ESD properties | Yes (for ESD version) |
| Caliper (Digital) | ±0.01mm accuracy | Dimensional verification | Yes |
| Multimeter | With high resistance range | Basic ESD testing | Optional |

### 4.2 Calibration Standards

| Item | Description | Specification | Purpose |
|------|-------------|---------------|---------|
| ESD Reference Standard | 10⁶, 10⁹ Ω/sq | IEC 61340-2-3 | Meter calibration |

---

## 5. Packaging & Storage Materials

| Item | Description | Quantity | Purpose |
|------|-------------|----------|---------|
| ESD-Safe Bag | Metallized shielding bag | 1 per piece | Storage and transport (ESD version) |
| Desiccant Pack | Silica gel, 5g | 1 per piece | Moisture control |
| Label | Self-adhesive, ESD warning | 1 per piece | Identification and safety |

---

## 6. Documentation & Certification

### 6.1 Required Documentation

- [ ] Material Certificate of Compliance (CoC) from filament manufacturer
- [ ] ESD test report (IEC 61340-5-1) for printed part
- [ ] Dimensional inspection report
- [ ] Traceability label with batch/serial number

### 6.2 Recommended Certifications

- IEC 61340-5-1 (ESD Protection)
- ISO 9001 (Quality Management) - for manufacturing facility
- IATF 16949 (Automotive Quality) - for automotive applications

---

## 7. Cost Estimation (Approximate)

| Item | Cost per Unit | Notes |
|------|---------------|-------|
| ESD Filament (50g) | $3 - $5 USD | Based on 1kg spool at $60-100 |
| Standard Filament (50g) | $1 - $2 USD | Based on 1kg spool at $20-40 |
| Print Time | ~2-3 hours | Depends on printer and settings |
| Testing (ESD version) | $10 - $20 USD | If outsourced |

**Total Cost per Unit (ESD):** ~$15 - $30 USD (including testing)  
**Total Cost per Unit (Non-ESD):** ~$2 - $5 USD

---

## 8. Supplier Information

### 8.1 Recommended Suppliers

**North America:**
- MatterHackers (www.matterhackers.com)
- 3DXTech (www.3dxtech.com)
- Protopasta (www.proto-pasta.com)

**Europe:**
- 3D Prima (www.3dprima.com)
- Kimya (www.kimya.fr)
- Fillamentum (www.fillamentum.com)

**Asia:**
- Polymaker (www.polymaker.com)
- eSUN (www.esun3d.com)

---

## 9. Revision History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 2.0 | 2026-02-14 | Added non-ESD version, expanded material list, added testing requirements | Valentino Hesse |
| 1.0 | 2025-01-XX | Initial BOM | Valentino Hesse |

---

## 10. Notes

1. **ESD Material Verification:** Always verify ESD properties after printing. Material properties can vary between batches.

2. **Storage:** Store ESD filament in sealed bags with desiccant. Moisture absorption can affect ESD properties.

3. **Print Environment:** Print in controlled environment (20-25°C, 40-60% RH) for consistent results.

4. **Traceability:** Maintain records of material batch numbers for automotive compliance.

5. **Alternative Materials:** Contact manufacturer before using materials not listed here.

---

**Document Owner:** Valentino Hesse  
**Last Updated:** 2026-02-14  
**License:** CERN-OHL-P v2  
**Repository:** https://github.com/Hessevalentino/Pyramid-PCB-Inspection-Fixture

