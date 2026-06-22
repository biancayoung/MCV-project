# Component Design: CNC Slide-Out Drawer

This document details the engineering specifications for the heavy-duty drawer designed to house the **Makera Carvera Air CNC** within the MCV.

---

## 🛠 Technical Specifications

| Feature | Specification |
| :--- | :--- |
| **Machine** | Makera Carvera Air CNC |
| **Machine Weight** | ~30 kg (66 lbs) |
| **Machine Footprint** | 500mm (W) x 450mm (D) |
| **Max Height (Lid Open)** | 840 mm |
| **Drawer Extension** | Full Extension (500mm) |
| **Mounting Type** | Side-mounted (Heavy Duty) |

---

## 📐 Design Concept: "The Reinforced U-Channel"

To support the 30kg CNC machine in a mobile environment, the drawer is designed as a reinforced **U-Channel** instead of a flat plank. This provides vertical walls for secure slide mounting and prevents the base from sagging.

### 1. Hardware Selection (Heavy-Duty Locking Slides)
*   **Recommended Models:** 
    *   **Accuride 9308E:** The professional standard for van builds (227kg rating).
    *   **Vadania VA2053:** High-value alternative (120kg rating).
    *   **Aolisheng Heavy Duty:** Cost-effective industrial option (120kg+).
*   **Essential Feature:** **Lock-in / Lock-out** mechanism is mandatory to prevent accidental movement during driving or operation.
*   **Length:** 500mm (20 inches).

### 2. CNC Assembly & Joinery
*   **Base Plate:** 15mm Plywood (500mm x 450mm).
*   **Side Walls:** 15mm Plywood "Cleats" (approx. 50mm height) attached to the base.
*   **Joinery:** Use **Blind Dado** or **Tab and Slot** joints for the side-to-base connection. This maximizes gluing surface and provides mechanical resistance against the machine's weight.
*   **Fasteners:** Avoid screwing into the plywood edge. Instead, **bolt through** the 15mm side walls using M5/M6 bolts and Nyloc nuts to attach the slides.

---

## 🔩 Installation Logic (Aluminum Integration)

Because we are using a **30/30 T-slot system**, the mounting process is modular:

1.  **Slide Attachment:** The outer member of the drawer slide is fastened to the T-slots of the vertical aluminum profiles using **M6 T-nuts** and button-head screws.
2.  **Leveling:** The height is set to allow the CNC lid to clear the upper cabinet frame (840mm total clearance required).
3.  **Drawer Attachment:** The inner member is bolted through the vertical plywood side walls of the drawer assembly.

---

## ⚠️ Critical Considerations for Vanlife/Mobile Labs

1.  **Vibration Dampening:** T-slot fasteners can vibrate loose. Use **Threadlocker (Blue Loctite)** on all slide-to-frame mounting screws.
2.  **Safety Lock:** A secondary manual latch (barrel bolt or toggle clamp) is recommended in addition to the slide's internal lock to ensure the 30kg machine stays put during emergency braking.
3.  **Cable Management:** Use a "Drag Chain" or flexible conduit for the CNC's power and USB cables to ensure they don't pinch or snag when the drawer is extended 50cm.

---
[Return to Stage 2 Process](STAGE_2.md) | [Back to Index](../INDEX.md)
