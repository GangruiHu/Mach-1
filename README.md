800mm 3D-Printed Flying Wing Pusher Plane
Making RC Flight Cheap and Accessible

This is an 800mm fixed-wing RC plane you can build for around $100 using 3D-printed parts, off-the-shelf electronics, and common hardware. The design uses a pusher motor configuration (propeller in back) for clean airflow over the wings, and elevons (mixed control surfaces) for pitch and roll.

The goal is simple: prove that serious RC flying doesn't need to cost hundreds of dollars. This plane can fly stably, turn predictably, and teach you real aeromodeling skills without the sticker shock.

Design Overview

What makes this plane special:

Entirely 3D-printed structure – wings, tail, fuselage, all printed at home
Light and efficient – about 1.4 kg (3 lbs), flies on a small 2S LiPo battery
Simple to build – pusher config, no complex assembly, epoxy and screws hold it together
Durable materials – PLA for main structure, PETG for high-stress parts like the tail
Low infill – only 8% gyroid infill keeps weight down while maintaining strength

Flight characteristics:

Stable, predictable flyer – good for first flights
Efficient glider – can fly on low battery or catch thermals
Pushes about 8-10kg of thrust (plenty of power for 1.4kg plane)
Elevon control gives smooth, coordinated turns
Specifications
Spec	Value
Wingspan	800 mm
Weight (without battery)	~1.4 kg
Motor	Brushless outrunner, ~2200 kV
Battery	2S LiPo, 1500–2000 mAh
ESC	40A (rated for 2-6S)
Servos	2× 9g digital/analog servos
Receiver	Standard micro RC receiver (IBUS or PWM)
Flight time	8–12 minutes
Build time	6–8 hours (after prints finish)
Bill of Materials (BOM)

All components are sourced from Amazon for fast shipping and easy returns. Total: ~$100

#	Component	Qty	Price	Link	Notes
1	Motor – Brushless outrunner, 2200kV	1	$10	YAG-RX-2JJ3 Motor	177mm, 1080v, perfect size for this airframe
2	ESC – 40A brushless controller, 2-6S	1	$12	40A Brushless ESC	3V 1A BEC, XT60 connector
3	Battery – 2S LiPo, 1500–2000 mAh	1	$8	2S LiPo Battery	Turbo rated, XT60 connector
4	Charger – LiPo balance charger	1	$6.99	LiPo Balance Charger	Silicone lead, XT60 and balance plugs
5	Receiver – Micro RC receiver (IBUS)	1	$15	35A Micro Receiver	IBUS protocol, dual PWM output, failsafe
6	Servos – 9g digital/analog servos	2	$12	9g Servo Set	Two servos for elevon control
7	Motor mount hardware	1	$3	Self-sourced	M3 screws, aluminum angle, bolts
8	Propeller – 5×4.5" pusher prop	1	$5.99	Propeller Set	Two-blade, 5×4.5 for pusher config
9	Connectors – XT60/AS150 adapters	1 pack	$8	Power Connectors	Gold-plated, reliable
10	Wires – 18 AWG silicone, XT60/bullet plugs	1 pack	$6	Silicone Power Cable	Battery to ESC, ESC to motor
11	Servo linkage rods	1 pack	$5.99	Servo Pushrod Set	Clevises and threaded rods
12	Hinge pins (1mm steel wire)	1 pack	$10.99	Stainless Steel Rod	1.5×300mm, cut to length for elevon hinges
13	Carbon tube (spar) – 4mm OD	2 ft	$5	Self-sourced	Wing reinforcement, ~2× 400mm pieces
14	Foam tape & adhesive	1	$3	Hardware store	3M foam tape for servo mounting
15	M2 and M3 assorted screws	1 box	$5	Hardware store	Servo mounting, motor mount, tail mount
16	CA glue + epoxy	1 ea	$4	Hardware store	Hinge pins, joint reinforcement
17	3D-printed parts	–	$0*	Your printer	Wings, fuselage, tail, hatch (PLA + PETG)

Estimated Total: ~$105–115 (before 3D printing filament, which you may already have)

3D printing filament cost is minimal if you already own a printer (~$5–10 worth of PLA/PETG).

What You'll Print

The design provides all 3D models in Fusion 360 (see build files).

Part	Material	Infill	Notes
Wings (left + right)	PLA	8% gyroid	Use 2 walls, lightweight
Fuselage pod	PLA	8% gyroid	Nose, body, hatch
Elevons (left + right)	PLA	8% gyroid	Control surfaces, lightweight
Tail (vertical stabilizer)	PETG	8% gyroid	More impact-resistant than PLA
Servo retainers	PLA	8% gyroid	Hold servos in place
VTX bracket/tray	PETG	8% gyroid	Optional, for FPV camera if you add one later
Motor plate	PLA	15 layers bottom	Extra durability for motor mount
Nose plug (camera cap)	PLA	2 walls, 8%	Optional, closes nose when no camera

Print settings:

Nozzle temp: 210°C (PLA), 230°C (PETG)
Bed temp: 60°C (PLA), 80°C (PETG)
Speed: 40–50 mm/s
Layer height: 0.2 mm
Support: Tree supports where needed, especially on elevons
Assembly Steps (Quick Outline)
Print all parts – about 30–40 hours total print time across a few parts
Glue wing spars – epoxy carbon rods into wing channels (two 400mm pieces meeting at centerline)
Mount motor and ESC – bolt motor to motor plate using aluminum angle and plastic spacers
Install servos – use foam tape or servo retainers to mount inside fuselage
Glue hinge pins – 1mm steel wire through elevon hinges (CA glue, minimal play)
Wire up electronics – ESC → motor, battery connector to ESC, receiver to ESC/servos
Balance and test – hang on fishing line to find CG (should be around 250mm from nose)
First flight – trim elevons level, fly in calm weather
Why This Plane Costs ~$100
No proprietary parts – everything is Amazon or hardware-store standard
Clever design – elevons (one servo per surface, mixed in software) instead of separate servo per axis
Lightweight structure – 8% infill is strong enough; no waste
Reusable electronics – battery, servos, receiver, ESC work on future planes
3D printing is cheap – you make the airframe, not factories

A store-bought RC plane of similar size runs $200–400. This proves you don't need that.

Building Tips

Electronics:

Use a LiPo alarm on the battery – it beeps when voltage gets low
Program failsafe on your receiver (default: motor off, plane glides)
Pair your transmitter before first flight

Assembly:

Drill all holes before final glue-up – easier to get straight
Use small dabs of CA glue on hinge pins, not pools (excess melts plastic)
Check elevon centering before flying – they should be level with fuselage when neutral

Flying:

Start in calm air, large open field, with a buddy who can spot
Trim elevator and ailerons in slow, level flight
Expect first flights to be wobbly – practice on simulator first if possible
Bring spare battery and check linkages after each flight
Next Steps
Print the parts – start with wings and fuselage
Gather electronics – order from the BOM above
Build and balance – allow 8–10 hours of actual work
Maiden flight – give yourself time and space to learn
Add features later – FPV camera, longer wings for more lift, second battery for practice
Community & Support

This design was created to be open and hackable. Questions about:

Printing: try different infill %, try PETG instead of PLA for durability
Flying: join local RC clubs, watch YouTube (FliteTest is great), practice on simulators
Electronics: LiPo safety is critical – don't charge unattended, store in fireproof bag
Mods: stretch fuselage for more room, add struts, try folding prop for glide distance
Design Philosophy

Making RC flight cheap, simple, and fun for everyone.

This plane proves that:

You don't need expensive kit planes to learn aeromodeling
3D printing puts real aircraft design in your hands
A few dollars of parts and a few hours of work = weeks of flying

Fly safe. Build often. Keep it simple.

Files Included
flying_wing_800_pusher_v5.py – Complete Fusion 360 design (Python script)
nose_plug.stl – Optional nose cap (camera placeholder)
README.md – This file

Print STLs from Fusion, slice them in your slicer, and go.
