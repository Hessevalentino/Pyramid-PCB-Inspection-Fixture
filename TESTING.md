# Testing and Validation Protocol

## Pyramid PCB Inspection Fixture - Version 2.0

This document outlines the testing and validation procedures for the Pyramid PCB Inspection Fixture to ensure compliance with automotive Class 3 standards and ESD requirements.

---

## 1. Overview

### 1.1 Purpose
This testing protocol ensures that manufactured fixtures meet:
- ESD protection requirements (IEC 61340-5-1)
- Dimensional tolerances for PCB inspection
- Automotive Class 3 quality standards (IPC-A-610)
- Structural integrity requirements

### 1.2 Scope
- Applies to both ESD and non-ESD versions
- Required for automotive applications
- Recommended for all production units

---

## 2. Pre-Production Testing

### 2.1 Material Verification

**Test:** Filament Material Certificate Review  
**Frequency:** Each new batch/spool  
**Acceptance Criteria:**
- [ ] Material certificate from manufacturer present
- [ ] ESD properties certified (for ESD version)
- [ ] Batch/lot number traceable
- [ ] Expiration date valid (if applicable)

**Test:** Visual Filament Inspection  
**Frequency:** Before each print  
**Acceptance Criteria:**
- [ ] No visible contamination
- [ ] Consistent diameter
- [ ] No moisture bubbles or discoloration
- [ ] Proper storage conditions maintained

---

## 3. Post-Production Testing (ESD Version)

### 3.1 ESD Properties Testing

#### Test 3.1.1: Surface Resistivity Measurement

**Standard:** IEC 61340-2-3  
**Equipment Required:**
- Surface resistance meter (e.g., Prostat PRS-801, Trek 152)
- Two 5-pound electrodes
- Calibration standards (10⁶, 10⁹ Ω/sq)

**Procedure:**
1. Condition part at 23±3°C, 50±5% RH for minimum 24 hours
2. Calibrate meter using reference standards
3. Clean part surface with isopropyl alcohol, allow to dry
4. Place electrodes 25mm apart on flat surface
5. Apply 10V or 100V test voltage
6. Record resistance after 15 seconds
7. Test minimum 5 locations per part
8. Calculate average resistance

**Acceptance Criteria:**
- Surface Resistivity: 10⁶ - 10⁹ Ω/sq
- All measurements within specification
- Coefficient of variation < 20%

**Documentation:**
- Record all measurements
- Note test conditions (temperature, humidity)
- Operator signature and date

---

#### Test 3.1.2: Volume Resistivity Measurement

**Standard:** IEC 61340-2-3  
**Equipment Required:**
- Volume resistance meter
- Parallel plate electrodes

**Procedure:**
1. Condition part as per Test 3.1.1
2. Place part between parallel electrodes
3. Apply 100V test voltage
4. Record resistance after 60 seconds
5. Calculate volume resistivity

**Acceptance Criteria:**
- Volume Resistivity: 10⁴ - 10¹¹ Ω·cm

---

#### Test 3.1.3: Charge Decay Time

**Standard:** IEC 61340-5-1  
**Equipment Required:**
- Charge decay meter (e.g., Prostat CDT-2000)
- High voltage source (1000V)

**Procedure:**
1. Condition part as per Test 3.1.1
2. Charge part to 1000V
3. Measure time to decay to 100V
4. Repeat 3 times, record average

**Acceptance Criteria:**
- Decay time: < 2 seconds
- Consistent across all measurements

---

### 3.2 Dimensional Inspection

#### Test 3.2.1: Critical Dimensions

**Equipment Required:**
- Digital caliper (±0.01mm accuracy)
- Micrometer (for wall thickness)
- Reference drawing (pyramid.pdf)

**Measurements:**

| Dimension | Nominal | Tolerance | Measured | Pass/Fail |
|-----------|---------|-----------|----------|-----------|
| Base Width | [TBD]mm | ±0.5mm | _______ | ☐ |
| Base Length | [TBD]mm | ±0.5mm | _______ | ☐ |
| Height | [TBD]mm | ±0.5mm | _______ | ☐ |
| Wall Thickness | [TBD]mm | ±0.2mm | _______ | ☐ |
| PCB Contact Surface | [TBD]mm | ±0.3mm | _______ | ☐ |

**Note:** Fill in nominal dimensions from pyramid.pdf technical drawing

**Acceptance Criteria:**
- All dimensions within tolerance
- No warping or deformation
- Smooth surface finish on contact areas

---

### 3.3 Visual Inspection

**Standard:** IPC-A-610 Class 3  
**Equipment Required:**
- Magnification (10x minimum)
- Good lighting (>1000 lux)

**Inspection Points:**

| Defect Type | Acceptance Criteria | Result |
|-------------|---------------------|--------|
| Layer adhesion | No delamination visible | ☐ Pass ☐ Fail |
| Surface finish | Smooth, no rough edges | ☐ Pass ☐ Fail |
| Voids/gaps | None visible on exterior | ☐ Pass ☐ Fail |
| Stringing | None present | ☐ Pass ☐ Fail |
| Warping | < 0.5mm deviation | ☐ Pass ☐ Fail |
| Color uniformity | Consistent throughout | ☐ Pass ☐ Fail |
| Contamination | None visible | ☐ Pass ☐ Fail |

**Acceptance Criteria:**
- All inspection points must pass
- No Class 3 defects per IPC-A-610

---

### 3.4 Functional Testing

#### Test 3.4.1: PCB Stability Test

**Purpose:** Verify fixture holds PCB securely during inspection

**Procedure:**
1. Place standard PCB (e.g., 100x100mm) on fixture
2. Tilt fixture to 45° angle
3. Observe PCB stability
4. Apply gentle lateral force (50g)
5. Check for movement

**Acceptance Criteria:**
- PCB remains stable at 45° tilt
- No sliding under 50g lateral force
- No damage to PCB surface

---

#### Test 3.4.2: Microscope Compatibility Test

**Purpose:** Verify fixture fits under microscope

**Procedure:**
1. Place fixture with PCB under inspection microscope
2. Verify clearance for objective lens
3. Check stability on microscope stage
4. Verify PCB surface is in focus range

**Acceptance Criteria:**
- Adequate clearance for microscope objectives
- Stable on microscope stage
- PCB surface accessible for inspection

---

## 4. Post-Production Testing (Non-ESD Version)

For non-ESD version (pyramid-NOesd.stl), perform:
- Section 3.2: Dimensional Inspection
- Section 3.3: Visual Inspection  
- Section 3.4: Functional Testing

**Skip:** ESD properties testing (Section 3.1)

---

## 5. Environmental Testing (Optional but Recommended)

### 5.1 Temperature Cycling

**Purpose:** Verify dimensional stability

**Procedure:**
1. Measure critical dimensions at 23°C
2. Expose to 60°C for 4 hours
3. Cool to 23°C for 2 hours
4. Re-measure dimensions
5. Repeat for -10°C exposure

**Acceptance Criteria:**
- Dimensional change < 1%
- No cracking or deformation

---

### 5.2 Humidity Resistance

**Purpose:** Verify ESD properties remain stable

**Procedure:**
1. Test ESD properties at 50% RH
2. Expose to 85% RH for 24 hours
3. Re-test ESD properties

**Acceptance Criteria:**
- ESD properties remain within specification

---

## 6. Documentation Requirements

### 6.1 Test Report Template

Each tested unit must include:

```
PYRAMID PCB INSPECTION FIXTURE - TEST REPORT

Part Number: PYRAMID-[ESD/NOESD]-V2.0
Serial Number: _______________
Manufacturing Date: _______________
Test Date: _______________
Operator: _______________

MATERIAL INFORMATION:
Filament Manufacturer: _______________
Material Type: _______________
Batch/Lot Number: _______________

TEST RESULTS:
☐ ESD Surface Resistivity: _______ Ω/sq (Pass/Fail)
☐ ESD Volume Resistivity: _______ Ω·cm (Pass/Fail)
☐ Charge Decay Time: _______ seconds (Pass/Fail)
☐ Dimensional Inspection: Pass/Fail
☐ Visual Inspection: Pass/Fail
☐ Functional Test: Pass/Fail

OVERALL RESULT: ☐ PASS ☐ FAIL

Notes: _________________________________

Approved by: _______________
Date: _______________
```

### 6.2 Traceability Label

Affix label to each unit:
```
PYRAMID PCB FIXTURE
S/N: _______________
Date: _______________
Material: _______________
☐ ESD SAFE ☐ NON-ESD
Tested: ☐ Yes
```

---

## 7. Calibration Requirements

### 7.1 Test Equipment Calibration

| Equipment | Calibration Frequency | Standard |
|-----------|----------------------|----------|
| Surface Resistance Meter | Annual | NIST traceable |
| Calipers | Annual | ISO 17025 |
| Charge Decay Meter | Annual | NIST traceable |

---

## 8. Failure Analysis

### 8.1 Common Failures and Corrective Actions

| Failure Mode | Possible Cause | Corrective Action |
|--------------|----------------|-------------------|
| ESD out of spec | Moisture absorption | Dry filament, re-print |
| Dimensional error | Print settings | Adjust temperature/speed |
| Warping | Bed adhesion | Improve bed prep, enclosure |
| Layer delamination | Low temperature | Increase nozzle temp |
| Surface defects | Contamination | Clean nozzle, fresh filament |

---

## 9. Revision History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 2.0 | 2026-02-14 | Added non-ESD testing, expanded protocols | Valentino Hesse |
| 1.0 | 2025-01-XX | Initial testing protocol | Valentino Hesse |

---

**Document Owner:** Valentino Hesse  
**Last Updated:** 2026-02-14  
**License:** CERN-OHL-P v2  
**Repository:** https://github.com/Hessevalentino/Pyramid-PCB-Inspection-Fixture

