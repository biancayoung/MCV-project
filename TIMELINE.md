Project Navigation:  
[Index page](INDEX.md) | [Resources](RESEARCH_LOG.md)

---

# Build Timeline

## PHASE ONE
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **April 2** | **Project Kick-off:** First site visit of the Geely Farizon Super Van. | Done |
| **April 8** | **Digital Twin:** 3D Scan imported; Mesh section workflow established. | Done |
| **April 10**| **Version 1:** Recreated MayCAD assembly in Fusion 360. | Done |
| **April 14**| **Version 2:** CNC integration, frame swap, and material pivots. | Done |
| **April 16**| **BOM Finalized:** Orders sent for aluminum and wood panels. | Done |
| **April 17**| **Legal:** Vehicle registration completed. | Done |
| **Apr 18-19**| **Branding:** Exterior painting and decal application. | Done |
| **April 20**| **Assembly (Day 1):** Parts arrived; 9-hour assembly marathon in Huizhou. | Done |
| **April 21**| **Assembly (Day 2):** Frames installed; on-site wood trimming at Seeed Studio. | Done |
| **April 22**| **Launch:** Inauguration, Expo display, and Official Departure. | Done |

## PHASE TWO
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **MAY 17** | Research and buy heavy-duty drawer slides. | Done |
| **MAY 21** | **CNC drawer design:** Finish the design for the CNC drawer. | Done |
| **MAY 22** | Order the wood boards for the drawer slide.  | Done |
| **MAY 25**| Finished installing the CNC drawer.  | Done |

## Design Improvements and additions
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **MAY 21** | Plan and discuss the placement for some of the Seeed hardware to showcase. | Done |
| **MAY 22** | Design, 3D print, and install the custom holders for the Seeed hardware onto the van. | Done |

## System Setup
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **MAY 17** | **Set up the reCamera demo:** Set up a reCamera live heatmap demo in the van. | Done |

---

## Detailed Log of Events

### April 2: Kick-off
My involvement in the MCV Project officially began on April 2nd, 2026, when I was first introduced to the Geely Farizon Super Van. The timeline was exceptionally tight, with a fixed departure date of April 22nd, leaving a 20-day window for both design and implementation. At the start of this phase, the van was still undergoing license plate registration and inspection, which meant no physical modifications could be made to the vehicle. 

This limitation presented our greatest challenge: the entire interior had to be designed as a complete, finalized digital system before any physical assembly began. Unlike typical van conversions that span months of iterative building, this project relied entirely on high-precision digital planning and pre-fabrication. It’s also worth mentioning that our team - consisting of 冯老师 (Feng Lei), Spencer Yan, and myself - had no prior experience converting a van or building a mobile makerspace. 

### April 8: 3D Scan Setup
I began working with the 3D scan of the van's interior provided by 冯老师. This was my first time working with the interior of a vehicle and using a mesh as a reference at this scale. I researched established workflows and utilized the "Create Mesh Section Sketch" tool in Fusion 360. By taking horizontal and vertical slices of the scan, I created a "Digital Twin" envelope that ensured our structure wouldn't interfere with the physical van's ribs or curves.

### April 10-14: Iterative Design
After a basic block mockup, I moved to **Version 1**, recreating 冯老师’s MayCAD assembly in Fusion 360 piece-by-piece to allow for custom wood joinery design. Initially, we planned for a large 3D printer on the floor, but I quickly realized the ergonomics were terrible for cable access and filament feeding. 

The shift to **Version 2** was triggered by the addition of a **Maker Z1**. To accommodate its 30kg weight and 84cm lid height, I swapped the frame widths (making the left side wider) and designed a lifting counter space with heavy-duty drawer slides for maintenance access. Due to time, we replaced custom wood walls with acrylic sheets - a necessary pivot to meet the deadline. The CNC drawer was also put on pause and was left for later to be completed.

### April 16-17: BOM Finalization
Finalizing the BOM was a high-stress sprint. The manufacturer only accepted whole numbers for dimensions, forcing us to round up our 0.5mm offsets. 冯老师 and I also had to manually convert the Fusion 360 frame back into MayCAD to generate the automated BOM for screw hole placements. Orders were sent on the 16th, and the van was successfully registered on the 17th.

### April 20: Frame Assembly
The parts arrived on April 20th, and we immediately headed to a garage in Huizhou. The assembly was far more complex than imagined - 60+ nearly identical components mixed together. We spent hours sorting by size and figuring out the specific tightening sequence and hole orientations. We worked until 11:20 PM to finish the primary frames, and then worked the next morning until the afternoon to complete the process. We also had to make some on-site modifications to the aluminum structure when it was being installed into the van, as there were some extruded parts of the van we didn't notice until later.

### April 21: Installation & Tuning
On the 21st, we moved the frames into the van and secured them to the chassis. Back at the Seeed Studio office, those rounded-up 0.5mm offsets came back to bite us; some boards wouldn't fit. 冯老师 and the team took turns with a metal-cutting circular saw to shave down the edges. Once the panels were finally secured, I could step back as the rest of the team took over the electronics and demo setup.

### April 22nd: Inauguration & Departure
The project reached its climax at 10:00 AM on April 22nd with the official inauguration and live demos. After a public expo showcase and a symbolic departure ceremony in the afternoon, the van officially set off on its journey. It was a proud moment to see a bare shell transformed into a functional mobile lab in exactly 20 days. But this isn't the end, as many things still need to be improved and built as the van makes its journey.

### April 23rd to May 9th: Next Steps
After the van took off, I stayed back at Seeed's Shenzhen office to complete other work and study the SenseCAP line of sensors and devices to prepare to join the van in Chengdu.

### May 11th: Chengdu
I flew from Shenzhen Bao'an International Airport to Chengdu Shuangliu International Airport on the 11th, arriving in the evening at around 8:00 PM. I then hailed a DiDi to the dorms and settled in. The next morning, I had breakfast with Spencer, the tech lead onboard the van. We ate Dan Dan noodles (担担面, Dan Dan Mian) and then headed to the maker space to meet with the team. 

For the following days in Chengdu we worked in the maker space. I focused on improving the van, redesigning and making the CNC drawer, and we also had to find some places to display the hardware we brought along with us in the van, such as the SenseCAP products, reCamera, and Grove sensors.

Simultaneously, the design work and improvements were sometimes made on the road. During our stay in Chengdu, we drove the van to schools and science museums on certain days. On the days we were on-site, not a lot of design work was done. Instead, I focused on helping set up the van for the site visits and also setting up the reCamera. This was done whenever I was inside the van, as I had the reCamera set up and running on one of the reComputers inside the van.

It is also worth mentioning that our team setup had changed by this point. Spencer stayed with us for a few days in Chengdu before leaving. He had originally set off from Shenzhen with Feng Lei on the van and had already been traveling for around a month. At the Chaihuo space, I met 夏夏 (Xiaxia) and 叶子 (Yezi), as well as a new addition to our team, 浩楠 (Haonan). While I worked on the reCamera, Haonan worked on the Reachy Mini we had onboard, as he was taking over Spencer's role as the tech lead of the van.

---
**Project Navigation:**  
[Index page](INDEX.md) | [Timeline](TIMELINE.md) | [Stage 1: Assessment](process/STAGE_1.md) | [Stage 2: Design](process/STAGE_2.md) | [Stage 3: Assembly](process/STAGE_3.md) | [Resources](RESEARCH_LOG.md)
