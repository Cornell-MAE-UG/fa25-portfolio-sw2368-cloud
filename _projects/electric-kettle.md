---
layout: project
order: 4
title: Electric kettle energy model
course: MAE 2210
summary: Mass, energy and entropy balances for an electric kettle, and what insulating its walls would change.
technologies: [Thermodynamic modeling]
image: /assets/images/2210/2210_1.png
imagealt: Illustration of an electric kettle with its heating element labeled
---

An electric kettle takes in electrical energy and turns it into heat through Joule heating in its element. No mass crosses the boundary, only energy, so the water can be treated as a closed system.

![Control mass diagram: electrical work enters the fixed water and heat leaves to room air]({{ "/assets/images/2210/Control_Mass_Image.png" | relative_url }}){: .inline-medium}

## Balances

Mass stays constant:

<p class="eq"><i>dm</i>/<i>dt</i> = 0</p>

Nothing moves, so kinetic and potential energy terms and work drop out of the energy balance. Electrical power enters as heat and losses go to room air:

<p class="eq"><i>mc</i> <i>dT</i>/<i>dt</i> = <i>P</i> − <i>UA</i>(<i>T</i> − <i>T</i><sub>∞</sub>)</p>

Treating the water as an incompressible liquid gives the entropy balance:

<p class="eq">(<i>mc</i>/<i>T</i>) <i>dT</i>/<i>dt</i> = <i>Q̇</i><sub>in</sub>/<i>T</i> − <i>Q̇</i><sub>out</sub>/<i>T</i><sub>∞</sub> + <i>Ṡ</i><sub>gen</sub></p>

## Design change

Insulating the walls lowers the heat transfer coefficient *U*, which reduces the power needed to raise the water by the same temperature.
