[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources Log](../RESEARCH_LOG.md)

---

# Stage 2: Digital Design

## Contents
- [3D Scan Reference](#3d-scan-reference)
- [MayCAD to Fusion 360](#maycad-to-fusion-360)
- [Design Iterations (V1 vs V2)](#design-iterations-v1-vs-v2)
- [Final BOM & Tolerances](#final-bom--tolerances)

---

Following the initial inspection and research phase, the priority shifted to creating a precise digital twin of the van. The main constraint was time, with only 20 days to move from a bare shell to a finished mobile lab. Since the van was undergoing registration and could not be physically modified, every design decision had to be finalized in software before a single piece of aluminum was cut.

---

### 3D Scan Reference
I began working with a 3D scan of the van's interior. This was my first time working with the interior of a vehicle and using a mesh as a reference at this scale. I utilized the "Create Mesh Section Sketch" tool in Fusion 360 to create sketches where the van mesh intersected an offset plane. This allowed me to generate solid, workable geometry without crashing the computer with a massive mesh file. By taking horizontal sections for the floor and vertical sections for the walls and roof irregularities, I created a guide to ensure the structure would not interfere with the physical van's ribs or curves. This also helped in deciding the most logical placement for crucial equipment.

### MayCAD to Fusion 360
After a basic block mockup, I began recreating the initial aluminum structure in Fusion 360. While the physical mockup provided a great sense of scale (see Stage 1), we needed a high-fidelity digital assembly to handle the complex wood joinery and integration parts. Because MayCAD does not export assemblies as STEP files, I had to manually recreate the structure piece-by-piece. I used McMaster-Carr components and the "Q" (Press/Pull) command to match the dimensions, eventually mirroring the left and right frames perfectly in the digital space.

---

## Design Iterations (V1 vs V2)

To bridge the gap between digital modeling and real-world placement, we moved through two major design iterations to optimize equipment layout and access:

| Feature / Component | Iteration V1 (First Draft) | Iteration V2 (Final Digital Model) | Reason for Change |
| :--- | :--- | :--- | :--- |
| **3D Printer** | Large printer on the floor | Bambu Lab A1 Mini (Bench level) | Optimized floor space, cable access, and filament feeding ergonomics. |
| **Left Frame Width** | Standard width | Widened left frame | Custom fit to support the weight and footprint of the CNC machine. |
| **CNC Machine** | Not integrated | Maker Z1 (Slide-out) | Added heavy-duty drawer slides for easy maintenance access. |
| **Interior Walls** | Custom plywood sheets | Sliding Acrylic panels | Swapped to meet tight scheduling constraints for fabrication. |

---

### Final BOM & Tolerances
Once Version 2 was fixed, I created SVGs of the wood outlines for the manufacturers. A major challenge arose when we learned the manufacturer only accepted whole numbers for dimensions. I had to round up all my 0.5mm offsets (designed for flush fits) at the last minute in the BOM. This caused significant anxiety, as I knew these discrepancies would require manual and on-site modifications during the final installation at the Seeed Studio office.

---
[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources Log](../RESEARCH_LOG.md)
