---
layout: project
title: Spaceship Design
description: Just a spaceship that I designed
technologies: [SolidWorks, Machining]
image: /assets/images/spaceship-design.jpg
---



Chosen System: Electric Tea Kettle



Photo of system:




Qualitative description of the device or system:

An electric tea kettle is a closed thermodynamic system containing water that is heated by an 
electrical resistor. The kettle takes electrical energy as its input and converts it into thermal energy 
through Joule heating in the heating element. This thermal energy is then transferred to the water, 
raising its internal energy and temperature. In our system no mass enters or leaves the kettle, as 
only energy crosses the boundary. Therefore, we assume that it behaves as a closed system with
controlled mass. 











System diagram:
![Control Mass Image](/assets/images/2210/Control_Mass_Image.png)

Mass balance, Energy balance, and Entropy balance equations: 

mass balance
dm/dt=0 
m=constent 

energy balance
E=U+KE+PE
dE/dt=dQ/dt - dW/dt
dU/dt+d(KE)/dt+d(PE)/dt=dQ/dt - dW/dt
dW/dt =0
dU/dt=mc(dT/dt)
dQ/dtin=P=power
dQ/dtout =heat losses=UA(T-Tinf)
d(KE)/dt=d(PE)/dt=0 b/c nothing is moving 
dU/dt=dQin/dt - dQout/dtt 
mc(dT/dt)=P-UA(T-Tinf)

entropy balance equations  
dSsys/dt=sum((dQk/dt)/Tk)+dSgen/dt
dSsys/dt=(dQin/dt)/T)-(dQout/dt)/Tinf)+dSgen/dt
Assume incompressible liquid 
mc(dT/dt)/T=(dQin/dt)/T)-(dQout/dt)/Tinf)+dSgen/dt




Describe a change to device or system design or operating conditions and then how that 
change influences device performance:

The change we have decided to make to our system is insulating the walls. This will decrease the heat transfer coefficient, which in turn decreases the power needed to change the temperature the same amount. 

