# Stage 4: Chengdu Modifications

> **Documenting hardware installations and technical adjustments made on-site in Chengdu.**
> 
> Following the van's departure from Shenzhen, this stage covers the work completed at the Chaihuo space in Chengdu, including the CNC drawer fabrication and hardware showcase setups.

## Team Logistics

| Date | Event | Description |
| :--- | :--- | :--- |
| **May 11** | Arrival | Flew from Shenzhen to Chengdu Shuangliu International Airport. |
| **May 12+** | Team Changes | Met with Xiaxia, Yezi, and Haonan. Haonan took over as the technical lead of the van from Spencer. |
| **Ongoing** | Site Visits | Drove the van to local schools and science museums for demonstrations. |

## Mechanical Adjustments · CNC Drawer

The initial CNC drawer design was put on pause in Shenzhen due to time constraints. In Chengdu, the drawer was finalized and installed to support the Maker Z1.

| Date | Task | Description |
| :--- | :--- | :--- |
| **May 17** | Sourcing | Researched and purchased heavy-duty drawer slides. |
| **May 21** | Design | Finished the CAD design for the CNC drawer. |
| **May 22** | Fabrication | Ordered the custom wood boards for the drawer slide. |
| **May 25** | Installation | Completed the physical installation of the CNC drawer in the van. |

### CNC Drawer Fabrication & Installation Journey

In Chengdu, I focused on a new design for the CNC drawer, ensuring we had updated, accurate measurements. Once the CAD design was completed, we ordered the custom wood panels to be cut and bought heavy-duty drawer slides from Taobao.

My original plan was to assemble and install everything myself. The ideal installation logic involved drilling two types of holes: a smaller pilot hole, followed by a larger counterbore hole that didn't go all the way through, just deep enough to embed the screw heads so they wouldn't stick out and interfere with the sliding mechanisms. However, the makerspace didn't have the necessary tools: we only had one size of drill bit and a limited supply of screws. Short on time, we decided to pack all the disassembled components onto the van and find a local "shifu" (master craftsman) later to help with the installation.

When we eventually arrived in Ya'an, Feng Lei found a local shifu who managed to finish the entire assembly in about an hour and a half. To my surprise, he chose to use a nail gun for much of the assembly. I wasn't very keen on this approach because I wanted everything to be as sturdy as possible to support the heavy CNC machine. However, he fired probably around 100 nails into the wood and reinforced the structure with standard screws, so it turned out surprisingly solid. While there were a few details I would have done differently, at the end of the day, it works. Most importantly, the CNC is no longer just sitting on the floor making it hard to reach!

## Hardware Showcase Integration

During the site visits, we needed dedicated display solutions for the Seeed Studio hardware brought along in the van.

| Task Focus | Technical Execution |
| :--- | :--- |
| **Hardware Mounts** | Designed, 3D printed, and installed custom holders for the SenseCAP products and Grove sensors onto the van walls (May 21 - May 22). |
| **reCamera Demo** | Set up a live heatmap demonstration using the reCamera. The demo was run locally off one of the reComputer units installed inside the van. |
| **Reachy Mini** | Haonan focused on setting up and maintaining the Reachy Mini robot onboard. |

### Display Design Workflow

#### Whiteboard Planning
To figure out the display layouts for the modules around the van, I started by drawing a doodle on the whiteboard. This helped me map out exactly where I wanted to place the hardware for each module (excluding anything that had already been set up). The main components we needed to put up for display included the reCamera, the SenseCAP data logger, the 4G data hub, various environmental sensors, and the Grove sensors.

#### Grove Sensors: Flat Display Board
From that whiteboard doodle, I moved directly into the digital design phase. The first and fastest components to design for were the Grove sensors. I simply laid them out on my notebook in a clean layout, took a reference picture, and carefully measured them with a caliper. Using Fusion 360, I designed a simple display board that featured the names of the sensors and dedicated slots for them to fit into. The plan was to attach the sensors to the board using strong double-sided tape. This allowed us to easily remove them to show people the back side of the modules during demonstrations, while also simplifying the design process so we could manufacture the displays as fast as possible.

#### SenseCAP Sensors: Custom Wall Mounts
For the SenseCAP display, I took a slightly different approach. My goal was to display the sensors (soil, humidity, and an air sensor) plugged into the 4G hub, all securely mounted to the wall of the van. This meant that the sensors required custom holders to screw into the wood paneling. I started by taking a photo of the target wall space. Then, using Krita, I brought in photos of the 4G data hub and the sensors to visually mock up the layout and ensure everything would fit comfortably in the available area.

Next, I took a top-down photo of the sensors with a caliper placed right beside them for scale. In Fusion 360, I imported this image as a canvas and calibrated it to the exact physical dimensions using the caliper reference in the photo. From there, I modeled the general shape of the sensor and built the custom holder around it. I also took further, more precise physical caliper measurements, relying on the imported canvas mainly as a reference for capturing complex curves and organic shapes. I left a -0.5mm clearance offset to ensure a snug fit, and then repeated this process for the other sensor holders. Thanks to this method, the design process was incredibly quick, and the 3D prints came out perfect on the first try. Finally, we screwed everything into the van wall, and the display was complete.

---
[Timeline](../TIMELINE.md) | [Stage 2: Design](STAGE_2.md) | [Stage 3: Assembly](STAGE_3.md) | [Stage 5: Final](STAGE_5.md) | [Resources Log](../RESEARCH_LOG.md)
