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
| **May 17** | Research and buy heavy-duty drawer slides. | Done |
| **May 21** | **CNC drawer design:** Finish the design for the CNC drawer. | Done |
| **May 22** | Order the wood boards for the drawer slide.  | Done |
| **May 25**| Finished installing the CNC drawer.  | Done |

## Design Improvements and additions
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **May 21** | Plan and discuss the placement for some of the Seeed hardware to showcase. | Done |
| **May 22** | Design, 3D print, and install the custom holders for the Seeed hardware onto the van. | Done |

## System Setup
| Date | Milestone | Status |
| :--- | :--- | :--- |
| **May 17** | **Set up the reCamera demo:** Set up a reCamera live heatmap demo in the van. | Done |

---

## Detailed Log of Events

### April 2: Kick-off
My involvement in the MCV Project officially began on April 2nd, 2026, when I was first introduced to the Geely Farizon Super Van. The timeline was exceptionally tight, with a fixed departure date of April 22nd, leaving a 20-day window for both design and implementation. At the start of this phase, the van was still undergoing license plate registration and inspection, which meant no physical modifications could be made to the vehicle. 

This limitation presented our greatest challenge: the entire interior had to be designed as a complete, finalized digital system before any physical assembly began. Unlike typical van conversions that span months of iterative building, this project relied entirely on high-precision digital planning and pre-fabrication. It’s also worth mentioning that our team, consisting of 冯老师 (Feng Lei), Spencer Yan, and myself, had no prior experience converting a van or building a mobile makerspace. 

### April 8: 3D Scan Setup
I began working with the 3D scan of the van's interior provided by 冯老师. This was my first time working with the interior of a vehicle and using a mesh as a reference at this scale. I researched established workflows and utilized the "Create Mesh Section Sketch" tool in Fusion 360. By taking horizontal and vertical slices of the scan, I created a "Digital Twin" envelope that ensured our structure wouldn't interfere with the physical van's ribs or curves.

### April 10-14: Iterative Design
After a basic block mockup, I moved to **Version 1**, recreating 冯老师’s MayCAD assembly in Fusion 360 piece-by-piece to allow for custom wood joinery design. Initially, we planned for a large 3D printer on the floor, but I quickly realized the ergonomics were terrible for cable access and filament feeding. 

The shift to **Version 2** was triggered by the addition of a **Maker Z1**. To accommodate its 30kg weight and 84cm lid height, I swapped the frame widths (making the left side wider) and designed a lifting counter space with heavy-duty drawer slides for maintenance access. Due to time, we replaced custom wood walls with acrylic sheets (a necessary pivot to meet the deadline). The CNC drawer was also put on pause and was left for later to be completed.

### April 16-17: BOM Finalization
Finalizing the BOM was a high-stress sprint. The manufacturer only accepted whole numbers for dimensions, forcing us to round up our 0.5mm offsets. 冯老师 and I also had to manually convert the Fusion 360 frame back into MayCAD to generate the automated BOM for screw hole placements. Orders were sent on the 16th, and the van was successfully registered on the 17th.

### April 20: Frame Assembly
The parts arrived on April 20th, and we immediately headed to a garage in Huizhou. The assembly was far more complex than imagined: 60+ nearly identical components mixed together. We spent hours sorting by size and figuring out the specific tightening sequence and hole orientations. We worked until 11:20 PM to finish the primary frames, and then worked the next morning until the afternoon to complete the process. We also had to make some on-site modifications to the aluminum structure when it was being installed into the van, as there were some extruded parts of the van we didn't notice until later.

### April 21: Installation & Tuning
On the 21st, we moved the frames into the van and secured them to the chassis. Back at the Seeed Studio office, those rounded-up 0.5mm offsets came back to bite us; some boards wouldn't fit. 冯老师 and the team took turns with a metal-cutting circular saw to shave down the edges. Once the panels were finally secured, I could step back as the rest of the team took over the electronics and demo setup.

### April 22nd: Inauguration & Departure
The project reached its climax at 10:00 AM on April 22nd with the official inauguration and live demos. After a public expo showcase and a symbolic departure ceremony in the afternoon, the van officially set off on its journey. It was a proud moment to see a bare shell transformed into a functional mobile lab in exactly 20 days. But this isn't the end, as many things still need to be improved and built as the van makes its journey.

### April 23rd to May 9th: Next Steps
After the van took off, I stayed back at Seeed's Shenzhen office to complete other work and study the SenseCAP line of sensors and devices to prepare to join the van in Chengdu.

### May 11th to 18th: Chengdu
I flew from Shenzhen Bao'an International Airport to Chengdu Shuangliu International Airport on the 11th, arriving in the evening at around 8:00 PM. I then hailed a DiDi to the dorms and settled in. The next morning, I had breakfast with Spencer, the tech lead onboard the van. We ate Dan Dan noodles (担担面, Dan Dan Mian). It was my first time trying this, and although it is considered not so spicy compared to other foods in Chengdu, I still struggled a bit with it. Hopefully, by the end of this trip, my spice tolerance will be much higher. We then headed to the maker space to meet with the team. 

For the following days in Chengdu, we worked in the maker space. I focused on improving the van, redesigning and making the CNC drawer, and we also had to find some places to display the hardware we brought along with us in the van, such as the SenseCAP products, reCamera, and Grove sensors.

Simultaneously, the design work and improvements were sometimes made on the road. During our stay in Chengdu, we drove the van to schools and science museums on certain days. On the days we were on-site, not a lot of design work was done. Instead, I focused on helping set up the van for the site visits and also setting up the reCamera. This was done whenever I was inside the van, as I had the reCamera set up and running on one of the reComputers inside the van.

It is also worth mentioning that our team setup had changed by this point. Spencer stayed with us for a few days in Chengdu before leaving. He had originally set off from Shenzhen with Feng Lei on the van and had already been traveling for around a month. At the Chaihuo space, I met 夏夏 (Xiaxia) and 叶子 (Yezi), as well as a new addition to our team, 浩楠 (Haonan). While I worked on the reCamera, Haonan worked on the Reachy Mini we had onboard, as he was taking over Spencer's role as the tech lead of the van.

### May 19th to 21st: Drawer Slides Design
I finished the design for the drawer slides and made the final decisions on the parameters and design style. The drawer design is split up into 3 different parts: the box which is attached to the aluminum frame, the drawer slides (hardware), and the actual drawer. The drawer is designed in a slightly different way from most designs; the surface the CNC will rest on is set on top of the side and back wall, instead of underneath. This is to maximize the load bearing of the structure. I also ordered the wood boards and heavy-duty drawer slides on Taobao so they would arrive in time for the installation.

### May 22nd: Hiking in Guangyuan
We spent the day exploring and went on a hike up the mountain at the Tangjiahe Nature Reserve in Guangyuan. The hike was truly amazing. We were completely immersed in nature and surrounded by vibrant greenery, with little waterfalls at almost every stop. After spending the last few days working in the cramped and sometimes uncomfortable confines of the van, this change of scenery was breathtaking. Fueled by two coffees, I felt especially energized, and reaching the peak of the mountain to take in the spectacular view was an unforgettable experience.

### May 23rd to 28th: Ya'an and the Start of Route 318
We visited the Giant Panda breeding and research base in Ya'an and took some time for sightseeing. Following this, we visited the Sichuan Ya'an Middle School for a special event celebrating Eric Pan's return to his alma mater, where we participated in engaging discussions and cultural exchanges with the students. 

On the 24th, I rushed to install the CNC drawer. Back at the makerspace in Chengdu, we didn't have the necessary tools and materials for the installation, so I had to pack the drawer components, boards, and hardware onto the van. Once we were in Ya'an, we found a local "shifu" (master craftsman) to help. In his small workshop, he used a nail gun and screws to assemble everything. While I wasn't fully on board with the use of a nail gun, we were short on options and time, and the entire installation only took about an hour and a half.

Afterward, we officially set off on the road, marking the beginning of our journey along the famous China National Highway 318 (Route 318). At this point, our traveling team had changed and expanded. While Xiajie (Xiaxia) and Yezi stayed behind in Chengdu, the core crew moving forward consisted of Feng Lei (team lead), Haonan, and myself. We were also joined by 邝钟伦 (Allen), who took on the role of our new tech lead, as well as Eric Pan, founder and CEO of Seeed Studio, his father, and Fanxiang, who traveled alongside us in a separate vehicle. For the trip along Route 318, I traveled on board this second vehicle.

As we drove further along the highway, the scenery began to shift dramatically. The lush, rich green mountains gave way to more rugged, rocky, and grassy hills. Slowly but surely, I could start to see the snow-capped mountains in the distance as we made our way through the Zheduo Mountain Pass toward Tagong. The higher we climbed, the more breathtaking the view became. The clouds had never seemed so close, and the sunset was truly otherworldly. The entire drive to Tagong after the initial ascent was incredibly beautiful. We had the van drive in front of us so we could capture some scenic shots of it as we passed by herds of yaks and a vast sea of rolling grassy hills, with the snow-capped mountains in the background.

We arrived in Tagong right around sunset, and by that point, the entire crew was spent. The altitude there is around 3,600 meters, and we were all suffering from a bit of altitude sickness. By the next morning, we were still feeling the effects, some more than others. I myself was not faring too well; growing up at around 10 meters above sea level didn't quite prepare me for my first time at such an extreme elevation. Still, we powered through. Fueled by local yak milk tea, we made our way to our first stop. There, we worked alongside the locals to set up a LoRaWAN and Meshtastic network designed to assist the local herders in tracking and tracing their livestock. We hit our first obstacle as soon as we began: the network from the van wasn't working properly, and we needed internet access to set up the M2 LoRaWAN gateway. This took quite a bit of troubleshooting, but eventually, we got it running. Picture this: Haonan, Allen, and myself sitting huddled over our laptops, feeling sick and moving very slowly, trying to get everything to work. We also set up a SenseCAP Meshtastic solar node and trackers, attaching some to the yaks and one to a drone. At some point, I think running around the highlands finally got to me, and I was out of commission for the rest of the day.

The next day, we decided it was best to move to a lower altitude. We had spent the previous day working at elevations between 3,600 and 4,000 meters, which pushed most of the team to our physical limits. Seeking some relief, we packed up and drove to our next destination: Yajiang. After leaving Tagong, the journey primarily consisted of driving, stopping for scenic views and breaks, and then driving some more. There wasn't much technical work involved during this leg, as the main focus was simply making our way toward Tibet and beyond. From Yajiang, we continued our drive onward to Litang, and eventually reached Batang.

Batang is situated right at the border of Tibet and marked the final stop of my journey with the van. Since I am not a Chinese national, traveling into Tibet is highly regulated and complicated. It requires more than just a valid Chinese visa and strictly limits the allowed modes of travel. I would have needed to be part of an official guided tour and would not be permitted to travel independently with the MCV crew or work on our technical projects. Because of these restrictions, I couldn't go any further, and Batang was the absolute limit of my adventure. 

We arrived in the city a few hours before sunset and got situated at our hotel. After resting for a bit, Haonan, Allen, and I went out to explore. I stopped by a few shops to buy some souvenirs, we visited a local exhibition we happened to pass by, and we spent time simply wandering the colorful streets. Later in the evening, we met up with the rest of the team for dinner and watched a local dance in the city square. To cap off the night, we found a KTV spot and sang until it was time to call it a day. The very next morning at 5:00 AM, Allen and I made our way to the bus station and caught a 14-hour bus ride all the way back to Chengdu.

### May 29th to 31st: Return to Chengdu
Allen had decided to accompany me back to Chengdu, as he wasn't faring too well with the altitude either, and to ensure I wouldn't have to make the long journey by myself. Once we arrived back in Chengdu, we spent our first day resting and recovering. Afterward, I headed back into the makerspace to work on designing a custom holder for the 3D printer's AMS Lite module. This concluded my travels and hands-on work with the MCV project.

### Final Thoughts
This was an incredible journey from start to finish. This project truly inspires me, not just from a design and maker standpoint, but from the community outreach aspect as well. Working directly with locals to create custom solutions, and bringing resources and education to remote areas, has been a phenomenal experience. Now, with AI becoming more and more ingrained in our day-to-day lives, knowing how to leverage it to our benefit is a skill that is essential for being part of this future we are building. But it is important not to let this wave carry us forward while leaving others behind.

A massive thank you to Seeed Studio, Chaihuo Maker Space, and the entire team who made this project possible. I wish the remaining crew safe travels and the best of luck on the rest of their incredible journey!

---
**Project Navigation:**  
[Index page](INDEX.md) | [Timeline](TIMELINE.md) | [Stage 1: Assessment](process/STAGE_1.md) | [Stage 2: Design](process/STAGE_2.md) | [Stage 3: Assembly](process/STAGE_3.md) | [Stage 4: Chengdu](process/STAGE_4.md) | [Stage 5: Final](process/STAGE_5.md) | [Resources](RESEARCH_LOG.md)
