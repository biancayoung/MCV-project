[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources Log](../RESEARCH_LOG.md)

---

# Stage 3: Assembly & Installation

## Contents
- [Heading to Huizhou](#april-20th-heading-to-huizhou)
- [Frame Assembly](#frame-assembly)
  - [Extrusion Sorting](#1-extrusion-sorting)
  - [Assembly Workflow](#2-assembly-workflow)
  - [Reference Modeling](#3-reference-modeling)
- [Frame Installation](#tuesday-afternoon-fitting-the-frames)
  - [Test Fitting](#1-test-fitting)
- [Panel Installation & Trimming](#panel-installation--trimming)
  - [Plywood Adjustments](#1-plywood-adjustments)
  - [Corner Clearance Adjustment](#2-corner-clearance-adjustment)
- [Summary of Stage 3](#summary-of-stage-3)

---

With the digital designs finalized, we entered the final, most demanding phase of the project: physical assembly and installation. On Monday, April 20th, we transitioned from the clean, high-precision environment of Fusion 360 to the noisy, high-pressure reality of a professional vehicle modification garage. With only a day and a half to turn a pile of parts into a completed installation before driving back to Shenzhen, this phase was a true trial by fire.

---

## April 20th: Heading to Huizhou

To carry out the work, we drove the van to a specialized car modification garage in a nearby city, **Huizhou**. This was the same garage where the van’s initial modifications had been made before I joined the project, such as installing the auxiliary AC unit, carrying out the hidden electrical wiring, and replacing the front seats with 360-degree swivel mounts. 

We returned to this garage because the van was scheduled for further heavy modifications at the same time:
*   Installing a custom roof rack
*   Mounting an extendable roof awning
*   Adding heavy-duty off-road utility headlights

While the garage crew worked on these exterior and structural vehicle upgrades, we set up our own workspace in the shop to assemble the interior framing.

---

## Frame Assembly

### 1. Extrusion Sorting
When we first unwrapped the aluminum extrusions, my immediate reaction was one of pure overwhelm. There were dozens of profiles stacked together. They looked almost identical in size, yet featured tiny, crucial variations, such as different hole orientations, counterbores, and slot placements. 

Having never assembled a complex extruded aluminum structure before, the learning curve was steep. 

To bring order to the chaos, I established a rigorous sorting process:
*   **Sorting by Length:** I arranged all the aluminum profiles into distinct piles by exact length.
*   **BOM Verification:** I cross-referenced every single pile with our Bill of Materials (BOM). This took much longer than anticipated because some profiles differed by only a single centimeter. Double-checking and triple-checking at this stage was tedious, but it was the only way to avoid catastrophic mistakes later.

### 2. Assembly Workflow
Once everything was sorted, we began the actual build:
*   **Floor Mapping:** We laid out the profiles on the floor to visualize the sub-assemblies.
*   **Deductive Engineering:** We checked the hole alignments, figured out the correct orientation for the hidden T-nuts and brackets, and began assembling the vertical frame sections.
*   **Tie-in bars:** Once the side frames were up, we added the horizontal cross-members that held the entire structure together.

This process was long, repetitive, and incredibly tedious. Because T-slot assemblies have strict installation sequences, we frequently found ourselves completing a section only to realize we had forgotten a crucial internal T-nut or put a bracket in the wrong order. We had to repeatedly disassemble, correct, and reassemble parts of the frame.

### 3. Reference Modeling
As the hours dragged on and the night grew later, keeping the 3D relationships straight in my head became incredibly challenging. To cope, I set up a two-laptop workstation on the garage floor:
*   **Laptop 1 (Personal):** Ran my native **Fusion 360** assembly. This allowed me to rotate, zoom, and inspect the joints dynamically from any angle to verify exact bracket positions.
*   **Laptop 2:** Displayed the technical CAD file provided by the manufacturer to cross-reference dimensions.

At times, as fatigue set in, the shapes and lines stopped making sense. But by systematically checking the model on one screen against the manufacturing drawing on the other, we kept pushing forward.

---

## Tuesday Afternoon: Fitting the Frames

By the afternoon of Tuesday, April 21st, after a day and a half of continuous assembly, the primary left and right frames were fully built. Simultaneously, the garage team finished the exterior roof rack, awning, and headlight installations.

### 1. Test Fitting
We maneuvered the heavy aluminum frames into the van for the first test fit. This step immediately revealed our first set of physical tolerance issues:
*   **The Issue:** In a couple of locations, the frames would not sit completely flush against the interior due to minor structural obstructions on the van floor.
*   **The Fix:** Fortunately, these were easily resolvable. We used tools on-site to cut off the protruding ends of a few extrusion profiles. Once modified, the frames slid perfectly into place and the garage team secured them directly to the van's chassis.

With the skeletons securely mounted inside the vehicle, we packed our tools, jumped in, and drove the van back to the Seeed Studio office in Shenzhen, parking it directly in front of the building.

---

## Panel Installation & Trimming

Arriving back at the office, our work was far from done. The frames were inside the van, but they were still bare skeletons. We had to install the custom 15mm plywood worktops and shelving boards using L-bracket attachments. This is where the challenges truly began.

### Plywood Adjustments (The 0.5mm Offsets)
The tight tolerances we designed in CAD meant that several pre-cut plywood boards were exactly **0.5 mm too wide** to fit between the aluminum pillars. This was due to rounding up our CAD dimensions to whole numbers for the manufacturer in Stage 2.

In a true display of on-site "MacGyvering", we pulled out a handheld circular saw in the office parking lot and carefully shaved a fraction of a millimeter off the edges of the boards until they slipped perfectly into place flush.

### Corner Clearance Error (The Template Mistake)
The top counter board on the right side of the frame was hitting the curved corner wall of the van, which leaned inward at an angle.

*How it happened:* We actually checked this constraint with a custom cardboard template earlier. However, we checked it against the *old mockup frame* which was unattached and sitting out of its final height/depth alignment, making our test template completely inaccurate.
 
*The Fix:* We marked the interference line, brought the heavy wood panel out to the pavement, and used a handheld circular saw to make a long, angled rip cut along the back edge to clear the curved wall.

---

## Summary of Stage 3

In just two intense days, we moved from a pile of unlabeled metal bars and oversized wood panels to a fully installed, custom-fitted structural interior. It was a physical and mental sprint that taught us the vital difference between digital perfection and real-world assembly tolerances. 

With the physical structure, workbench surfaces, and slide-out CNC mounts complete, the vehicle was ready for the final stage: running the electrical wiring, mounting the machines, and preparing for the official launch.

---
[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources Log](../RESEARCH_LOG.md)
