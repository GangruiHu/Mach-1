# 800mm 3D-Printed Flying Wing Pusher Plane

Making RC Flight Cheap and Accessible to All

## Overview

This is an 800mm fixed-wing RC plane you can build for around **$100** using 3D-printed parts, off-the-shelf electronics, and common hardware. The design uses a pusher motor configuration (propeller in back) for clean airflow over the wings, and elevons (mixed control surfaces) for pitch and roll.

The goal is simple: **prove that serious RC flying doesn't need to cost hundreds of dollars.** This plane can fly stably, turn predictably, and teach you real aeromodeling skills without the sticker shock.

## Design Highlights

- **Entirely 3D-printed structure** – wings, tail, fuselage, all printed at home
- **Light and efficient** – about 1.4 kg (3 lbs), flies on a small 2S LiPo battery
- **Simple to build** – pusher config, no complex assembly, epoxy and screws hold it together
- **Durable materials** – PLA for main structure, PETG for high-stress parts
- **Low infill** – only 8% gyroid infill keeps weight down while maintaining strength
- **Stable flyer** – predictable, good for learning
- **Pushes plenty of power** – 8-10kg thrust for 1.4kg plane

## Specifications

Wingspan: 800 mm
Weight (no battery): ~1.4 kg
Motor: Brushless outrunner, ~2200 kV
Battery: 2S LiPo, 1500–2000 mAh
ESC: 40A (rated for 2-6S)
Servos: 2× 9g digital/analog servos
Receiver: Standard micro RC receiver (IBUS or PWM)
Flight time: 8–12 minutes
Build time: 6–8 hours (after prints finish)

## Bill of Materials

All components from Amazon for fast shipping. Total: ~$100-115

| Item | Qty | Price | Link |
|------|-----|-------|------|
| Motor – Brushless outrunner, 2200kV | 1 | $10 | https://www.amazon.com/gp/product/B09WHLJ2GN |
| ESC – 40A brushless controller, 2-6S | 1 | $12 | https://www.amazon.com/gp/product/B0CWDSP8YS |
| Battery – 2S LiPo, 1500–2000 mAh | 1 | $8 | https://www.amazon.com/gp/product/B07Y6L4LF1 |
| Charger – LiPo balance charger | 1 | $6.99 | https://www.amazon.com/gp/product/B0G64L3JLM |
| Receiver – Micro RC receiver (IBUS) | 1 | $15 | https://www.amazon.com/gp/product/B0F318LP13 |
| Servos – 9g digital/analog servos | 2 | $12 | https://www.amazon.com/gp/product/B07MLR1498 |
| Motor mount hardware | 1 | $3 | Self-sourced |
| Propeller – 5×4.5" pusher prop | 1 | $5.99 | https://www.amazon.com/gp/product/B0F8R6VJJ8 |
| Connectors – XT60/AS150 adapters | 1 pack | $8 | https://www.amazon.com/gp/product/B07TSMNGHJ |
| Wires – 18 AWG silicone, connectors | 1 pack | $6 | https://www.amazon.com/gp/product/B0CWDSP8YS |
| Servo linkage rods | 1 pack | $5.99 | https://www.amazon.com/gp/product/B0F318LP13 |
| Hinge pins (1mm steel wire) | 1 pack | $10.99 | https://www.amazon.com/gp/product/B0F8R6VJJ8 |
| Carbon tube (spar) – 4mm OD | 2 ft | $5 | Self-sourced |
| Foam tape & adhesive | 1 | $3 | Hardware store |
| M2 and M3 assorted screws | 1 box | $5 | Hardware store |
| CA glue + epoxy | 1 ea | $4 | Hardware store |
| 3D-printed parts | – | $0* | Your printer |

*3D printing filament cost is minimal if you already own a printer (~$5–10 worth of PLA/PETG).*

## What You'll Print

Print settings: 8% gyroid infill, 0.2mm layer height, 210°C nozzle (PLA), 230°C (PETG)

Wings (left + right) - PLA - Lightweight main structure
Fuselage pod - PLA - Nose, body, hatch
Elevons (left + right) - PLA - Control surfaces, lightweight
Tail (vertical stabilizer) - PETG - Impact-resistant
Servo retainers - PLA - Hold servos in place
VTX bracket/tray - PETG - Optional, for FPV camera
Motor plate - PLA - 15 layers bottom for durability
Nose plug (camera cap) - PLA - 2 walls, 8% infill

Print time: ~30–40 hours total across all parts

## Assembly Steps

1. Print all parts (allow 30–40 hours)
2. Glue wing spars (epoxy two 400mm carbon rods meeting at centerline)
3. Mount motor and ESC (bolt to aluminum angle + plastic spacers)
4. Install servos (foam tape or servo retainers inside fuselage)
5. Glue hinge pins (1mm steel wire through elevon hinges, CA glue)
6. Wire up electronics (ESC → motor, battery → ESC, receiver → ESC/servos)
7. Balance and test (hang on fishing line, CG should be ~250mm from nose)
8. First flight (calm weather, open field, friend nearby to spot)

## Why This Plane Costs ~$100

- No proprietary parts – everything is Amazon or hardware-store standard
- Clever design – elevons (one servo per surface) instead of multiple servos
- Lightweight structure – 8% infill is strong enough, no waste
- Reusable electronics – battery, servos, receiver, ESC work on future planes
- 3D printing is cheap – you make the airframe, not factories

Store-bought RC planes of similar size run $200–400. This proves you don't need that.

## Building Tips

Electronics:
- Use a LiPo alarm on the battery – beeps when voltage gets low
- Program failsafe on receiver (default: motor off, plane glides)
- Pair your transmitter before first flight

Assembly:
- Drill all holes before final glue-up (easier to get straight)
- Use small dabs of CA glue on hinge pins, not pools (excess melts plastic)
- Check elevon centering before flying (should be level with fuselage when neutral)

Flying:
- Start in calm air, large open field, with a buddy who can spot
- Trim elevator and ailerons in slow, level flight
- Expect first flights to be wobbly – practice on simulator first if possible
- Bring spare battery and check linkages after each flight

## What's Next

- Print the parts – start with wings and fuselage
- Gather electronics – order from the BOM above
- Build and balance – allow 8–10 hours of actual work
- Maiden flight – give yourself time and space to learn
- Add features later – FPV camera, longer wings, second battery

## Philosophy

This design is open and hackable. Try different infill %, swap PETG for PLA, add struts, fold the prop, stretch the fuselage. The goal is to put real aircraft design in your hands for less than $100.

Questions? Join local RC clubs, watch FliteTest on YouTube, practice on simulators, and don't be afraid to experiment.

## Safety

- **LiPo batteries:** never charge unattended, store in fireproof bag, don't over-discharge
- **Maiden flight:** calm weather, large field, spotter, check linkages before flying
- **First-time flyers:** use a simulator, watch tutorials, learn from mistakes on the ground

## Files Included

flying_wing_800_pusher_v5.py – Complete Fusion 360 design (Python script)
nose_plug.stl – Optional nose cap (camera placeholder)
README.md – This file

Print STLs from Fusion, slice in your slicer, and go.

---

Making RC flight cheap, simple, and fun for everyone.
