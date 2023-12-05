---
# layout: default
title: Nur Alif Ilyasa Project Showcase
site.title: anuan
---

This is Nur Alif Ilyasa's Project showcase of:

# CNC Machinery Build to Support Crocodile Art Small and Medium-sized Enterprise

## Background
I constructed two CNC machines, a Router CNC and a CO2 laser engraving CNC, to aid Crocodile Art, a small and medium-sized enterprise owned by my father. Specializing in crafting wooden handicrafts such as cutlery, wall decorations, and furniture, the motivation behind creating these CNC machines was to fulfill the business's need for a cost-effective solution. Prior to this endeavor, I demonstrated my proficiency by successfully assembling a functional 3D printer, driven by my passion for creative endeavors. This track record of accomplishment instilled confidence in my father, leading him to entrust me with the construction of the CNC machines for the benefit of Crocodile Art.

## Router CNC
<iframe width="560" height="315" src="https://www.youtube.com/embed/v8DaKf72d24?si=NLAdN24aU6jgjJb8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Crafted using Fusion 360, the CNC design posed a significant challenge as it mandated the selection of cost-effective components capable of reliably executing woodworking tasks. Rigorous research on existing CNC designs and specifications was imperative for this purpose. The CNC boasts a workable dimensional area of 2000x1250x250mm along the X, Y, and Z axes, respectively. Employing 20mm round linear rails on all axes, the linear rail choice was a crucial factor in ensuring optimal performance. Movement of the spindle is orchestrated by a NEMA 34 stepper motor, paired with a 12mm screw drive.

The spindle itself is a 12000RPM 2.2Kw motor featuring an ER20 tool clamping system. Due to the absence of a 3-phase electricity supply, a 2.2Kw inverter is incorporated into the design. The comprehensive build, encompassing these specifications, comes at an estimated cost of approximately 2500 USD.

The frame construction employed 40x60mm steel extrusion coupled with a 12mm steel plate, ensuring robustness for the machine. The entire frame received a coating of green paint for a polished finish. The welding process played a pivotal role in guaranteeing the sturdiness of the machine frame. Notably, aligning the two linear rails posed a challenge, as perfect perpendicularity was imperative to prevent potential carriage obstruction. Despite initial hurdles, meticulous alignment efforts proved successful, ensuring the smooth movement of the spindle carriage.

Concerning the electrical and computational components, Mach3, a widely used CNC board, was chosen. The controller comprises a PC and a Mach3 USB board, facilitating the precise control of actuators. Following calibration procedures, the CNC system is primed and ready for operation.

## CO2 Laser Engraving CNC
The fabrication of the CO2 Laser CNC was expedited, utilizing a Fusion 360 design acquired for 5 USD from furtherfabrication.com. Despite possessing a pre-existing design, numerous modifications were necessary to align with the availability of parts, a challenge exacerbated by the difficulty of sourcing reasonably priced CNC components in Indonesia.

The CNC incorporates a 60W CO2 laser tube, directing the laser through mirrors to precisely align it on the target medium. Employing 3D-printed components, the machine utilizes 10mm belts and pulleys, coupled with NEMA 17 stepper motors, to drive its operations.

Initially opting for an 8-bit microcontroller running GRBL for control, the limitations of speed and step skipping prompted a shift to a 32-bit Lightburn Laser controller, ensuring swift and precise engraving capabilities.

Driven by a time-sensitive need, upon completion, the CNC machine swiftly entered production, laser-engraving an impressive 150,000 wooden cutlery products within a month. Remarkably, the machine generated sevenfold profit within this period, operating incessantly to meet the stringent deadline.

[Demo video 1] (https://www.youtube.com/shorts/3cBtyi7PRRc)
[Demo video 2] (https://www.instagram.com/s/aGlnaGxpZ2h0OjE4MTI3NjU2MTAwMTUxNDQ0?igshid=MTc4MmM1YmI2Ng==)
