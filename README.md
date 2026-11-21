# 3D CAD Modeling & Mechanical Assembly Portfolio — SolidWorks

**Author:** Kushal L (`@kushallokesh24` | `@kushaldeaignme`)  
**Software:** SolidWorks Premium (MMGS Units)  
**Portfolio Website:** [https://github.io](https://github.io)

---

## Overview
A collection of 3D parametric part models and multi-component mechanical assemblies modeled in **SolidWorks**, demonstrating sketching across reference planes, Boolean features, chamfers/fillets, slot/keyway cuts, bottom-up assembly mating, and Bill of Materials (BOM) structuring.

---

## 1. Featured Assembly: 5-Component Knuckle Joint

![Knuckle Joint 3D Assembly](knuckle_joint_assembly.png)

### Component Breakdown & Materials (BOM)

| Item | Component Name | Material | Qty | Key Dimensions & Features |
| :--- | :--- | :--- | :---: | :--- |
| 1 | **Fork End** | Forged Steel (`FS`) | 1 | `Ø60 mm` outer eye, `Ø30 mm` pin bore, `36 mm` jaw gap, `R18 / R36` fillets, `147 mm` overall length |
| 2 | **Eye End** | Forged Steel (`FS`) | 1 | `Ø60 mm` outer eye, `Ø30 mm` bore, `36 mm` eye thickness, `33 × 33 mm` flat transition, `120 mm` length |
| 3 | **Knuckle Pin** | Mild Steel (`MS`) | 1 | `Ø45 × 15 mm` head, `Ø30 × 102 mm` shank with `Ø6 mm` cross-hole for taper pin locking |
| 4 | **Collar** | Mild Steel (`MS`) | 1 | `Ø45 mm` OD, `Ø30 mm` ID, `15 mm` height with aligned taper pin bore |
| 5 | **Taper Pin** | Mild Steel (`MS`) | 1 | `Ø6 mm` nominal diameter, `60 mm` length, `1:30` standard taper |

### SolidWorks Techniques Applied
- **Bottom-Up Assembly Mating:** Concentric and coincident face mates aligning the Fork End, Eye End, Pin, Collar, and Taper Pin while preserving `1 DOF` rotational articulation without part interference.
- **2D Engineering Drawing Interpretation:** Modeled directly from standard orthographic/isometric production specifications in `MMGS`.

---

## 2. Parametric 3D Part Modeling Collection

### A. Flanged Tapered Sleeve / Bushing with Keyway Slot
![Flanged Tapered Sleeve](flanged_tapered_sleeve.png)
- **Features Used:** Cylindrical base flange extrusion, tapered/chamfered upper collar, concentric through-bore, and axial rectangular keyway/slot cut.
- **Design Focus:** Shaft-hub alignment and concentricity for mechanical power transmission components.

### B. Slotted Wedge / Tapered Support Block
![Slotted Wedge Support Block](slotted_wedge_support.png)
- **Features Used:** Rectangular base plate extrusion, inclined triangular profile extrusion, and internal U-slot cut.
- **Design Focus:** Multi-profile sketching and material removal for structural support brackets.

### C. 3-Axis Orthogonal Interlocking Cross Joint
![3-Axis Cross Joint](orthogonal_cross_joint.png)
- **Features Used:** Multi-plane sketching (Front, Top, and Right reference planes) with symmetric mid-plane extrusions.
- **Design Focus:** Spatial coordinate alignment and symmetric feature creation across orthogonal axes.

---

## Repository Contents
- `*.SLDPRT` / `*.SLDASM` — Native SolidWorks part and assembly files
- `*.STL` / `*.STEP` — Universal 3D geometry files for browser preview and CAD interoperability
- `*.png` — High-resolution isometric renders
