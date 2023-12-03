---
# layout: default
title: Nur Alif Ilyasa Project Showcase
site.title: anuan
---

This is Nur Alif Ilyasa's Project showcase of:

# CNC Machinery Build to Support Crocodile Art Small and Medium-sized Enterprise

## Background
I built 2 CNC machine which are a Router CNC and a CO2 laser engraving CNC to support a small and medium-sized enterprise Crocodile Art. Crocodile Art is actually my father's bussiness. We usually made various kind of wooden handycrafts, mostly cultery, wall decoration, and furniture. The CNC was made since my father as the owner of the bussiness wanted a low-cost CNC machine. Before I build these CNC machines, I successfully built a working 3D printer just to support my creation hobby. because of this, My Father belives me that I can build a CNC for him.

## Router CNC
The CNC is designed in Fusion 360. The design is a challange since I need to pick parts that are cheap but can reliably handle the job of woodworking. This requires research of existing CNC design and specification. The CNC has workable dimension area 2000x1250x250mm on respective X Y Z axis. The linear rail that we choose is 20mm round linear rails on all axis. To drive the movement of the spindle, NEMA 34 stepper motor is utilized along with 12mm screwdrive. The spindle is 12000RPM 2.2Kw motor with ER20 tool clamping system. Since we don't have 3 phase electricity supply an 2.2Kw inverter is used. In total, the build cost around 2500USD.

For the frame, we used 40x60mm steel extrution and 12mm steel plate. The frame then coated with green paint. The build involves a welder to make sure that the machine frame is sturdy enough for our machine. Here we encontered a challange when the 2 linear rail needs to be perfectly perpendicullar, otherwise the carriage could stuck and wont able to move. However, after several alignment we were able to make it perpendicullar and the spindle carriage can move smoothly.

In terms of electricity and computer, we used Mach3 wich is a common board for CNC machine. The controller consist of a PC and Mach3 USB board, control the actuators. After some calibration the CNC is ready to be used.

## CO2 Laser Engraving CNC
The CO2 Laser CNC was made in a rush. Same as before I use Fusion 360 to draw the CNC design. However, I use a design which I paid for 5USD from furtherfabrication.com. Although I have a finished design, there are many parts that are needed modifications adapting with the avability of the parts. Finding CNC parts in Indonesia is hard especially when we want reasonable price.

The CNC uses 60W CO2 laser tube, the laser from the tube is reflected with the mirrors to align it on the target medium. Several 3D printing parts is used to build this CNC machine. 10mm belts and pulleys along with NEMA 17 stepper motor is used to drive the CNC machine. 

For the controller I tried to use 8bit based microcontroller to run GRBL. However this controller can't drive the motor fast. If it goes to fast, it suffers step skipping. So, we gave up GRBL and bought a Lightburn Laser controller which is 32bit based controller that enables fast engraving.

As we needed the machine ASAP, when the machine is done and ready to take orders, the machine is imideatelly used to laser 150000 of wooden cultery products. In just one month the machine has made 7x in profit of the cost to build the Laser engraving machine. In this period the machine operates non stop to chase the deadline.


