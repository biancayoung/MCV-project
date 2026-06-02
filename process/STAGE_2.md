# Stage 2: Digital Design & Technical Implementation

Following the initial inspection and research phase, the priority shifted to creating a precise digital twin of the van. The main constraint was time, with only 20 days to move from a bare shell to a finished mobile lab. Since the van was undergoing registration and could not be physically modified, every design decision had to be finalized in software before a single piece of aluminum was cut.

---

### Mastering the 3D Scan (April 8th)
I began working with a 3D scan of the van's interior. This was my first time working with the interior of a vehicle and using a mesh as a reference at this scale. I utilized the "Create Mesh Section Sketch" tool in Fusion 360 to create sketches where the van mesh intersected an offset plane. This allowed me to generate solid, workable geometry without crashing the computer with a massive mesh file. By taking horizontal sections for the floor and vertical sections for the walls and roof irregularities, I created a guide to ensure the structure would not interfere with the physical van's ribs or curves. This also helped in deciding the most logical placement for crucial equipment.

### The MayCAD to Fusion Translation
After a basic block mockup, I began recreating the initial aluminum structure in Fusion 360. While the physical mockup provided a great sense of scale (see Stage 1), we needed a high-fidelity digital assembly to handle the complex wood joinery and integration parts. Because MayCAD does not export assemblies as STEP files, I had to manually recreate the structure piece-by-piece. I used McMaster-Carr components and the "Q" (Press/Pull) command to match the dimensions, eventually mirroring the left and right frames perfectly in the digital space.

### Iteration V1: Ergonomics and Placement
I established a few core parameters: we would use 15mm plywood for all surfaces, with worktops sitting on the frame and internal shelves sitting flush using L-brackets. In the first version, we planned to put a large 3D printer on the floor, but I quickly realized this would make cable access and filament feeding nearly impossible. We moved the printer to the workbench level to ensure accessibility and protect it from accidental damage on the floor.

### Iteration V2: Integrating the CNC
The design pivoted again when we confirmed the addition of a **Makera Carvera Air CNC**. This machine, weighing 30kg and requiring 84cm of clearance for the lid, forced us to widen the left frame. I designed a specialized cabinet where the counter space lifts up and the CNC sits on a heavy-duty drawer slide for easy maintenance. Due to time constraints, we also decided to swap custom wood walls for acrylic sheets that slide directly into the aluminum extrusion grooves. We also swapped the large 3D printer for a Bambu A1 Mini, which further optimized our space constraints.

### Final BOM and the 0.5mm Hurdle
Once Version 2 was fixed, I created SVGs of the wood outlines for the manufacturers. A major challenge arose when we learned the manufacturer only accepted whole numbers for dimensions. I had to round up all my 0.5mm offsets (designed for flush fits) at the last minute in the BOM. This caused significant anxiety, as I knew these discrepancies would require manual and on-site modifications during the final installation at the Seeed Studio office.

---
**Project Navigation:**  
[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources](../RESEARCH_LOG.md)
