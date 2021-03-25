# LTEBS_2021_II_Group_08_EAGLE

This repository contains the first project for the Electronic Technologies and Biosensors Laboratory course, part of the Biomedical Engineering MSc at Politecnico di Milano.
In this project we designed a schematic, a PCB and two custom components using Autodesk EAGLE. The aim of the work was to design a PCB embedding the PSoC 5LP micro-controller in order to evaluate its performance.

# PCB relevant info

- The PCB manufacturer is MDSrl and therefore we followed the rules explained on their website for PCB design (https://www.mdpcb.com/mddesignrules.html).
We used 6mils as minimum track width because the 10mils request could not be fulfilled within the MUX without clearance errors; so we imposed 6mils as minimum width (following manufacturer specs) but still used 10mils traces everywhere except for the MUX, where we used 8mil traces.
- We positioned the light sensor as far away as possible from the LED in order to avoid luminous interference given by the LED. We also tried to position the light sensor as isolated as possible from "tall" components in order to avoid shadows that could interfere with the sensor's measurements.
- We positioned the temperature sensor as far away as possible from the power supply in order to avoid interference given by possible heating of the power supply.
- For the copper pour we used isolation 8 that is the minimum allowed by the manufacturer
