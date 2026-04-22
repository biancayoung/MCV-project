# Project Timeline: The 20-Day Sprint

| Date | Milestone | Status |
| :--- | :--- | :--- |
| **April 2** | **Project Kick-off:** First site visit of the Geely Farizon Super Van. | ✅ Done |
| **April 8** | **Digital Twin:** 3D Scan imported; Mesh section workflow established. | ✅ Done |
| **April 10**| **Version 1:** Recreated MayCAD assembly in Fusion 360. | ✅ Done |
| **April 14**| **Version 2:** CNC integration, frame swap, and material pivots. | ✅ Done |
| **April 16**| **BOM Finalized:** Orders sent for aluminum and wood panels. | ✅ Done |
| **April 17**| **Legal:** Vehicle registration completed. | ✅ Done |
| **Apr 18-19**| **Branding:** Exterior painting and decal application. | ✅ Done |
| **April 20**| **Assembly (Day 1):** Parts arrived; 9-hour assembly marathon in Huizhou. | ✅ Done |
| **April 21**| **Assembly (Day 2):** Frames installed; on-site wood trimming at Seeed Studio. | ✅ Done |
| **April 22**| **Launch:** Inauguration, Expo display, and Official Departure. | 🚀 Live |

---

## Detailed Log of Events

### April 2nd: The Project Kick-off
My involvement in the MCV Project officially began on April 2nd, 2026, when I was first introduced to the Geely Farizon Super Van. The timeline was exceptionally tight, with a fixed departure date of April 22nd, leaving a mere 20-day window for both design and implementation. At the start of this phase, the van was still undergoing license plate registration and inspection, which meant no physical modifications could be made to the vehicle. 

This limitation presented our greatest challenge: the entire interior had to be designed as a complete, finalized digital system before any physical assembly began. Unlike typical van conversions that span months of iterative building, this project relied entirely on high-precision digital planning and pre-fabrication. It’s also worth mentioning that our team—consisting of 冯老师 (Feng Lei), Spencer Yan, and myself—had no prior experience converting a van or building a mobile makerspace. 

### April 8th: Mastering the 3D Scan
I began working with the 3D scan of the van's interior provided by 冯老师. This was my first time working with the interior of a vehicle and using a mesh as a reference at this scale. I researched established workflows and utilized the "Create Mesh Section Sketch" tool in Fusion 360. By taking horizontal and vertical slices of the scan, I created a "Digital Twin" envelope that ensured our structure wouldn't interfere with the physical van's ribs or curves.

### April 10th - 14th: Iterative Design (V1 to V2)
After a basic block mock-up, I moved to **Version 1**, recreating 冯老师’s MayCAD assembly in Fusion 360 piece-by-piece to allow for custom wood joinery design. Initially, we planned for a large 3D printer on the floor, but I quickly realized the ergonomics were terrible for cable access and filament feeding. 

The shift to **Version 2** was triggered by the addition of a **Makera Carvera Air CNC**. To accommodate its 30kg weight and 84cm lid height, I swapped the frame widths (making the left side wider) and designed a lifting counter space with heavy-duty drawer slides for maintenance access. Due to time, we replaced custom wood walls with acrylic sheets—a necessary pivot to meet the deadline.

### April 16th - 17th: The Paperwork Sprint
Finalizing the BOM was a high-stress sprint. The manufacturer only accepted whole numbers for dimensions, forcing us to round up our 0.5mm offsets. I also had to manually convert the Fusion 360 frame back into MayCAD to generate the automated BOM for screw hole placements. Orders were sent on the 16th, and the van was successfully registered on the 17th.

### April 20th: The Assembly Marathon
The parts arrived on April 20th, and we immediately headed to a garage in Huizhou. The assembly was far more complex than imagined—60+ nearly identical components mixed together. We spent hours sorting by size and figuring out the specific tightening sequence and hole orientations. We worked until 11:20 PM to finish the primary frames.

### April 21st: Installation & "MacGyvering"
On the 21st, we moved the frames into the van and secured them to the chassis. Back at the Seeed Studio office, those rounded-up 0.5mm offsets came back to bite us—some boards wouldn't fit. 冯老师 and the team took turns with a metal-cutting circular saw to shave down the edges. Once the panels were finally secured, I could step back as the rest of the team took over the electronics and demo setup.

### April 22nd: Inauguration & Departure
The project reached its climax at 10:00 AM on April 22nd with the official inauguration and live demos. After a public expo showcase and a symbolic departure ceremony in the afternoon, the van officially set off on its journey. It was a proud moment to see a bare shell transformed into a functional mobile lab in exactly 20 days.
---
**Project Navigation:**  
[Timeline](TIMELINE.md) | [Stage 1: Assessment](process/STAGE_1.md) | [Stage 2: Design](process/STAGE_2.md) | [Resources](RESEARCH_LOG.md)

