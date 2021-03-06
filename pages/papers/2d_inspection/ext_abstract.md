---
title: Original Extended Abstract
layout: math_post
tags:
- papers
comments: true
---

## Abstract

Small satellites would make excellent inspection vehicles for investigating larger satellites on orbit. However, today’s technology for relative actuation has some glaring gaps - requiring contact or propellant. The forces between a magnetic field and its induced electric currents could control the relative position between a small chaser spacecraft and a larger target without physical contact. A system utilizing these eddy-current forces places relatively few requirements on the target and chaser compared to more exotic EM actuation systems. This paper presents a system overview of a contactless eddy-current actuator, outlines those requirements through the analysis of an inspection mission on the ISS, and compares them to current experimental work.  

When a million-dollar asset fails in space, engineers have only sensor readings for diagnosis.  This problem of on-orbit inspection could be solved by small satellites similar to the vehicles that now service deep-sea pipelines. However, while AUVs can maneuver around their targets by pushing water through propellers, smallSats have no such luxury. Current actuation technology is limited to conventional thrusters or grapplers. Both options have downsides. Thrusters require propellant and can damage sensitive surfaces of the target. Grapplers are similarly risky if the target doesn’t expect to be grabbed - as is the case with virtually all large targets currently in orbit. An inspection vehicle with a contactless actuator can avoid many of the problems with grapplers and thrusters. Enter eddy-current forces.

Eddy-current forces result from the interaction between a magnetic field and the current it induces in a conductive target. Eddy-current forces can be tangential to the targets’ surface as well as attractive and repulsive. Therefore, a small spacecraft generating a time-varying magnetic field could produce forces in all three translational degrees of freedom. Extending that idea, two sources of these forces separated by a moment arm could also produce torques to orient the spacecraft. 

Both moving permanent magnets and electromagnets with time-varying fields can generate eddy-current forces. A single electromagnet with a sinusoidal driving current will always produce a repulsive force between itself and the target, while replicating that signal with a permanent magnet would require either a closed-loop linear actuator or a complicated set of linkages. Similarly, the simple system comprising a permanent magnet mounted on a motor shaft produces horizontal shear forces between itself and the target. The advantages of different eddy-current generation methods suggests that a multi-degree-of-freedom actuator should utilize both electromagnets - for axial forces - and permanent magnets - for shear forces. 

Although they have many advantages, eddy-current actuators are not a killer app for generating 6-degree-of-freedom forces. Eddy-current forces are small and drop off quickly with distance. The necessary electromagnets and motors both generate thermal loads. While possible, it is difficult for an eddy-current actuator to generate a force that pulls the target and inspection vehicle closer together.

Despite these flaws, many applications can take advantage of this technology’s strengths (electric-only, propellantless, contactless forces with an uncooperative target) and minimizes its weaknesses. 

One application well suited for a small inspection vehicle equipped with an eddy-current actuator is inspecting a large metal object in orbit, like the ISS. An inspection satellite can take advantage of orbital effects across the surface of the ISS that will provide a constant relative force towards the surface, provided the satellite can produce the repulsive and shear forces to keep itself in place. Through the lense of that application this paper presents a system overview of a contactless eddy-current actuator, outlines its requirements, and compares them to current experimental work. 