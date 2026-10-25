---
title: Mach-1 800mm 3D-Printed Flying Wing Pusher Drone
author: Gangrui Hu
description: Designing an affordable RC plane with 3D-printed parts, targeting $100 total cost
created_at: 2026-10-24
---

# October 24th, Design Phase: CAD & Component Selection

Started designing the complete 800mm flying wing pusher aircraft in Fusion 360 using Python scripting. Focused on creating a lightweight, affordable plane that can be 3D-printed at home and assembled for under $100.

**Design decisions:**
- 800mm wingspan, ~1.4 kg total weight
- Pusher motor (clean airflow), elevon control surfaces
- Dual material strategy: PLA for main structure (wings, elevons, nose), PETG for high-stress parts (tail, VTX bracket)
- 8% gyroid infill for strength-to-weight ratio
- Motor plate with 15 bottom layers and plastic spacers (isolate from PETG fuselage)
- Wing spars: two 400mm carbon rods meeting at centerline
- Elevon hinges: 1mm steel wire (user-tested, <1mm play)

**Component shopping:**
- Brushless motor: 2200 kV outrunner ($10)
- 40A ESC 2-6S ($12)
- 4S LiPo battery 1500–2000 mAh ($8)
- Micro RC receiver with IBUS ($15)
- 2× 9g servos ($12 total, mismatched models OK if speed/throw matched)
- Propeller, connectors, wiring (~$35)
- Fasteners, adhesives, tape (~$13)
- **Total verified: $105–115**

Designed fuselage with flat nose face (34.0 × 33.8 mm ellipse), camera pocket (19.4 mm square), and lofted pod.

<img width="1210" height="696" alt="image" src="https://github.com/user-attachments/assets/097f138a-f495-44ec-bd5a-f509da893344" />

**Total time spent:** 4 hours

# October 25th: Printing and Assembly Phase

After 24 hours of printing, I got most of the plane body 3D printed, with the exception of the tail piece. I decided to test-fit the parts and do a mock-up before parts arrived to make sure everything fit. When I tried inserting the stepper motors into the slots, I realised I had made it too short, so I fought with a soldering iron and took the walls back so everything would fit. Then I took heated M3 inserts and pressed them all in, and I fitted everything together to see how it would come together. Everything seems to be going well for now.

<img width="720" height="960" alt="image" src="https://github.com/user-attachments/assets/ec2966f2-ceb7-4e5d-993c-f527399d78a2" />
<img width="960" height="720" alt="image" src="https://github.com/user-attachments/assets/1a5c0c6d-2e09-4475-9ae3-320449320228" />
<img width="960" height="720" alt="image" src="https://github.com/user-attachments/assets/76ba3321-590b-48f3-bd67-facf960bf7ac" />
<img width="960" height="720" alt="image" src="https://github.com/user-attachments/assets/d96828b0-8c7d-46cb-b075-1a56303f7801" />
<img width="960" height="720" alt="image" src="https://github.com/user-attachments/assets/057b4544-3651-4176-b355-4055915f4024" />

**Total time spent:** 2 hours



