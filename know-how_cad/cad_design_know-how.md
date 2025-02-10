# CAD Design (Know-how) 

## Tolerances   
   
### Part Designs: 

|   Desired Fit  |   Clearance Gap (mm)  |
| :---- | :---- |
|   **Threading (For Screws)**  |   Line to line  |
|   **Press Fit (Interference Fit)**  |   \< 0.05  |
|   **Tight Fit (Transition Fit)**  |   \< 0.10  |
|   **Normal Fit (Sliding Fit)**  |   \< 0.20  |
|   **Loose Fit (Clearance Fit)**  |   \> 0.25  |

* **Clearance Gap:** Clearance between object lines in total. E.g.: If a cylinder diameter is ⌀3 mm, the pillar diameter should be ⌀2.85 mm for a normal fit.
* The values are for Prusa MK3S printer and PETG material.
* For the PLA, lower the clearance gap slightly.
* **Threading:** Ideal when mounting is required without using bolts. E.g.: For an M3 screw, the hole diameter is 3 mm. 
* **Press Fit:** Suitable for snap-fit joints and friction assemblies.
* **Tight Fit:** Ideal for parts that need to stay together but still allow for manual assembly and disassembly.
* **Normal Fit:** Suitable for moving parts such as hinges, enclosures, and modular components.
* **Loose Fit:** Useful for hinges, guides, and other mechanisms requiring free movement.

## RPi HQ Cam Housing Design
   
![RPi HQ Cam Housing Design](./images/rpi_hq_cam_housing_design.png)
   
## Tripod Holder
   
### Master Sketch:   
![Tripod Holder Master Sketch](./images/tripod_holder_master_sketch.png)
   
### Sub-Sketches:
![Sub-Sketch 1](./images/tripod_holder_sub_sketch_1.png)
![Sub-Sketch 2](./images/tripod_holder_sub_sketch_2.png)
![Sub-Sketch 3](./images/tripod_holder_sub_sketch_3.png)
![Sub-Sketch 4](./images/tripod_holder_sub_sketch_4.png)
![Sub-Sketch 5](./images/tripod_holder_sub_sketch_5.png)
   
## Rail System
   
![Rail System](./images/rail_system.png)
   
## 28byj-48 Stepper Motor Shaft Nest

* Master Sketch (Tight (0.10 mm) \- Press Fit (0.05 mm)):  
![Master Sketch](./images/stepper_motor_master.png)

* Hole depth (5.1mm): 2.5 mm 
![Hole Depth](./images/stepper_motor_solid_1.png)

* Notch depth: 8.50 mm 
![Notch Depth](./images/stepper_motor_solid_2.png)
   
## M3 Square Nut Nest Design

* Notch depth: 7.75 mm 
![Notch Depth](./images/m3_square_nut_nest_1.png)

* Hole diameter: 3 mm;   
* Hole depth: 6 mm; 
![Hole Dimensions](./images/m3_square_nut_nest_2.png)
   
## M3 Screw Head or Hex Nut Embedded Design (Circle)

* Diameter: 6 mm 
![Diameter](./images/m3_hex_nut_nest_1.png)

* Hole depth: 3 mm 
![Hole Depth](./images/m3_hex_nut_nest_2.png)
   
## M3 Hex Nut Embedded Design

* Width across corners: 6.35 mm   
* Width across flats: 5.50 mm   
* Edge: 3.18 mm   
* Depth: 2.5 mm  
![Dimensions](./images/m3_hex_nut_nest_3.png)
   
## Screw Head Design

* Master Sketch 
![Master Sketch](./images/screw_head_1.png)

* Pad length: 4.5 mm 
![Pad Length](./images/screw_head_2.png)

* Circle diameter: 5.4 mm   
* Pocket depth: 3 mm 
![Dimensions](./images/screw_head_3.png)

* Pad length: 1 mm   
* Taper Angle: \-10°   
* Inner Angle: 10° 
![Angles](./images/screw_head_4.png)
   
## Pillar/Rivet Design

* RPi 5 Hole: ⌀2.7 mm (As an example)   
* Pillar Diameter \= ⌀2.5 mm; Pillar Length \= 4 mm   
* Head Diameter \= ⌀5 mm; Head Length \= 4 mm   
* Head Hole Diameter \= ⌀2.65 mm; Head Hole Depth \= 3 mm 
   
### Example:

* Original Screw Hole: ⌀4.3 mm    
* Pillar Diameter \= ⌀4.15 mm, Pillar Length \= 7 mm   
* Head Diameter \= ⌀6.5 mm, Head Length \= 15 mm   
* Head Hole Diameter \= ⌀4.3 mm, Head Hole Depth \= 6 mm 
![Example](./images/rivet_master.png)
![Rivet](./images/rivet.png)
   
## Bearing Design
   
Ref: [https://www.thingiverse.com/thing:2375124](https://www.thingiverse.com/thing:2375124)    
   
**V7:** 

| Parameter Name  | Dimension (mm)  |
| :---- | :---- |
| GapFit  | 0.10  |
| GapSlide  | 0.27  |
| NumRolls  | 20  |
| RollDiameter  | 8.08  |
| ScrewDiameter  | 3  |
| NumScrews  | 12  |

* MasterTopView Sketch 
![Top View](./images/bearing_design_top_master.png)

* MasterSideView Sketch 
![Side View](./images/bearing_design_side_master.png)
