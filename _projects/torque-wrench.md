---
layout: project
order: 3
title: Titanium torque wrench
course: MAE 3270
summary: Sizing a strain-gauged 3/8 in. torque wrench against strength, fracture and fatigue requirements, then checking the hand calculations with finite elements.
technologies: [MATLAB, ANSYS Mechanical, Fusion 360]
image: /assets/images/3270_fem.png
imagealt: ANSYS normal stress plot of the deflected wrench handle
---

The wrench is a non-ratcheting 3/8 in. design with a Ti-6Al-4V handle, rated at 600 in-lbf, with a half-bridge strain gauge reading the handle's bending. I sized a 0.50 in. square section in a MATLAB script, then modeled it in Fusion 360 and ANSYS.

![Dimensioned Fusion 360 sketch of the handle's square section]({{ "/assets/images/3270_1.png" | relative_url }}){: .inline-small}

## Requirements

All four design requirements passed in the hand calculations.

| Requirement | Target | Calculated |
|---|---|---|
| Strength safety factor | at least 4.0 | 4.79 |
| Fracture safety factor | at least 2.0 | 3.32 |
| Fatigue safety factor | at least 1.5 | 2.08 |
| Bridge output at 600 in-lbf | at least 1.0 mV/V | 1.80 mV/V |

## Hand calculations against FEM

| Result | Hand calculation | ANSYS |
|---|---|---|
| Maximum normal stress | 28.8 ksi | 72.4 ksi |
| Load-point deflection | 0.778 in. | 0.880 in. |
| Axial strain at gauge | 1800 microstrain | 871 microstrain |

Mesh lines across the handle stayed straight as it deformed, so the beam theory assumption that plane sections remain plane held up. The ANSYS peak stress is much higher than the hand value, and it sits at the clamped end. The wrench is not a slender prismatic beam, and beam theory leaves out the local 3D stress concentrations there.

![ANSYS normal stress plot of the wrench handle]({{ "/assets/images/3270_fem.png" | relative_url }})
