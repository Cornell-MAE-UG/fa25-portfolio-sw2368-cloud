---
layout: project
order: 2
title: Vibrating lanternfly trap
course: MAE 2250, client project for Cornell CALS Extension
summary: A pesticide-free column that vibrates at 60 Hz to attract spotted lanternflies, then kills them on an electrified mesh.
technologies: [Fusion 360, 3D printing, Gear train design, PhyPhox]
image: /assets/images/2250/cross-section.png
imagealt: Hand-drawn cross section of the column, showing the gear train, internal cam and zapping mesh
---

Spotted lanternflies are damaging vineyards in New York, and pesticides risk contaminating the grapes. Our team of five, Guardians of the Grapevine, worked with Cornell CALS Extension, E&J Gallo Winery and National Grape on a control method that uses no chemicals.

<div class="figure-pair" markdown="0">
  <figure>
    <img src="{{ "/assets/images/2250/prototype.png" | relative_url }}" alt="Finished prototype: a mesh-wrapped pole standing on a white base with a power adapter">
    <figcaption>Final prototype</figcaption>
  </figure>
  <figure>
    <img src="{{ "/assets/images/2250/cross-section.png" | relative_url }}" alt="Hand-drawn cross section showing the pole, zapping cage, soft internal cam, gear train and motor">
    <figcaption>Cross section of the final design</figcaption>
  </figure>
</div>

## How it works

A DC motor drives a gear train and cam inside a polycarbonate pole, and the cam's impacts vibrate the pole. Lanternflies are drawn to the 60 Hz vibration and land on two layers of aluminum mesh separated by zip ties. An insect touching both layers completes the circuit.

## Testing and changes

| Test | First prototype | What we changed | Final prototype |
|---|---|---|---|
| Vibration frequency | 25 Hz | Reworked the gear ratios for 3600 rpm at the driven shaft | 60 Hz |
| 5 minutes of continuous running | Wooden cam damaged the pole | Switched to a softer rubber cam inside the tube | No wear or failure |
| Lateral force | 5 N without deformation | Narrowed the base plate opening to reduce pole movement | 10 N without deformation |

The final prototype met all three success criteria, and we recommended moving to field testing in a vineyard. Professor V. Hunter Adams advised us that a speaker would produce low frequencies better than a motor, which we listed as a future change since budget ruled it out here.

## Documents

- [Client pitch (PDF)]({{ "/assets/grapevine-client-pitch.pdf" | relative_url }})
- [Final client report (PDF)]({{ "/assets/grapevine-client-report.pdf" | relative_url }})
