# Stage 3: Assembly & Installation

With the digital designs finalized, we entered the final, most demanding phase of the project: physical assembly and installation. On Monday, April 20th, we transitioned from the clean, high-precision environment of Fusion 360 to the noisy, high-pressure reality of a professional vehicle modification garage. With only a day and a half to turn a pile of parts into a completed installation before driving back to Shenzhen, this phase was a true trial by fire.

---

## April 20th: Heading to Huizhou

To carry out the work, we drove the van to a specialized car modification garage in a nearby city, **Huizhou**. This was the same garage where the van’s initial modifications had been made before I joined the project—such as installing the auxiliary AC unit, carrying out the hidden electrical wiring, and replacing the front seats with 360-degree swivel mounts. 

We returned to this garage because the van was scheduled for further heavy modifications at the same time:
*   Installing a custom roof rack
*   Mounting an extendable roof awning
*   Adding heavy-duty off-road utility headlights

While the garage crew worked on these exterior and structural vehicle upgrades, we set up our own workspace in the shop to assemble the interior framing.

---

## Frame Assembly

### 1. Extrusion Sorting
When we first unwrapped the aluminum extrusions, my immediate reaction was one of pure overwhelm. There were dozens of profiles stacked together. They looked almost identical in size, yet featured tiny, crucial variations—such as different hole orientations, counterbores, and slot placements. 

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

### 1. The First Test Fit
We maneuvered the heavy aluminum frames into the van for the first test fit. This step immediately revealed our first set of physical tolerance issues:
*   **The Issue:** In a couple of locations, the frames would not sit completely flush against the interior due to minor structural obstructions on the van floor.
*   **The Fix:** Fortunately, these were easily resolvable. We used tools on-site to cut off the protruding ends of a few extrusion profiles. Once modified, the frames slid perfectly into place and the garage team secured them directly to the van's chassis.

With the skeletons securely mounted inside the vehicle, we packed our tools, jumped in, and drove the van back to the Seeed Studio office in Shenzhen, parking it directly in front of the building.

---

## Panel Installation & Trimming

Arriving back at the office, our work was far from done. The frames were inside the van, but they were still bare skeletons. We had to install the custom 15mm plywood worktops and shelving boards using L-bracket attachments. This is where the challenges truly began.

### 1. Plywood Adjustments
As anticipated during the design phase (detailed in [Stage 2](STAGE_2.md)), rounding up our 0.5mm offsets to whole numbers to satisfy the manufacturer's constraints came back to bite us.
*   **The Reality:** The tight tolerances we designed in CAD meant that several pre-cut plywood boards were exactly **0.5 mm too wide** to fit between the aluminum pillars. 
*   **The Fix:** In a true display of "MacGyvering" in the office parking lot, we pulled out a handheld circular saw and carefully shaved a fraction of a millimeter off the edges of the boards until they slipped perfectly into place.

### 2. Corner Clearance Adjustment
A much more severe issue arose with the top counter board on the right side of the frame. The board was hitting the curved corner wall of the van, which leaned inward at an angle rather than going straight up.
*   **Why we missed it:** We actually *knew* about this wall curvature constraint during the design phase. We had even gone into the van with a custom cardboard template to check if the wood would clear the wall. 
*   **The Mistake:** When we did that cardboard check, we tested it against the *old mockup frame* which was unattached, sitting out of its final alignment, and not sitting at the correct height or depth. This meant our template check was completely inaccurate.
*   **The On-Site Solution:** With the board physically wedged against the metal wall, we marked the interference line, brought the heavy wood panel out to the pavement, and used the handheld circular saw to make a long, angled rip cut along the back edge. 

After adjusting the cut, the counter board cleared the angled van wall beautifully and sat flush on the frame.

---

## Summary of Stage 3

In just two intense days, we moved from a pile of unlabeled metal bars and oversized wood panels to a fully installed, custom-fitted structural interior. It was a physical and mental sprint that taught us the vital difference between digital perfection and real-world assembly tolerances. 

With the physical structure, workbench surfaces, and slide-out CNC mounts complete, the vehicle was ready for the final stage: running the electrical wiring, mounting the machines, and preparing for the official launch.

---
**Project Navigation:**  
[Timeline](../TIMELINE.md) | [Stage 1: Assessment](STAGE_1.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Resources](../RESEARCH_LOG.md)
