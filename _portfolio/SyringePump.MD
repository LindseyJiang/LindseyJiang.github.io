---
title: "Syringe Pump"
excerpt: "This design project used modern techniques of filament 3D printing and microcontroller programming to design a functional syringe pump."
header:
  image: /assets/img/syringepumpreallifeassembly.gif
  teaser: /assets/img/syringepumpreallifeassembly.gif
gallery:
  - url: /assets/img/syringepumpcadmodel.jpg
    image_path: assets/img/syringepumpcadmodel.jpg
    alt: "placeholder image 1"
  - url: /assets/img/syringepumpwiringdiagram.png
    image_path: assets/img/syringepumpwiringdiagram.png
    alt: "placeholder image 2"
---

This design project used modern techniques of filament 3D printing and microcontroller programming to design a functional syringe pump. The project supports 20 mL and 10 mL syringes. Two syringe pump diameters were used to calculate maximum flow rates. A 14.3 mm diameter syringe’s maximum flow rate is 12.044 mL/min. A 19.2 mm diameter syringe would have a maximum flow rate of 21.713 mL/min. 

## Parts List
#### Off-the-shelf

| Name          | Quantity      | 
| ------------- |:-------------:| 
| Computer with USB port | 1 | 
| Power supply | 1 | 
| Arduino | 1 |   
| Stepper motor | 1 |    
| Lead screw | 1 |
| Screws for housing | 4 |
| Latching button | 1 |
| Limit switch | 1 |
| LED | 1 |
| Breadboard | 1 |
| Jumper wires | 1 |
| 20 mL or 10 mL syringe | 1 |
| V-slot 20 x 40 x 350 mm | 1 |

Syringe Specifications:
* Plunger base diameters: 12 mm - 20.75 mm 
*	Flange diameters: 17 mm - 38.5 mm
*	End of plunger diameter: < 17 mm 
*	Barrel diameter: 21.50 mm 


#### 3D printed parts 

| Name          | Quantity      | 
| ------------- |:-------------:| 
| Component housing box and lid | 1 |
| End support | 2 |
| Motor mounting plate | 1 |
| Carriage | 1 |

## [Arduino Code](/assets/SyringePumpCode.md)

## CAD Model 
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811b450b96097101e87?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Operating Instructions: 
1.	Work on a clean, flat surface away from liquids.
2.	Fill the appropriately sized syringe with the desired amount of liquid
3.	Gather the syringe pump, computer, Arduino cable, and power supply. Check that all device connections are secure.
4.	Rotate the lead screw to position the carriage for the syringe.
5.	Place the loaded syringe into the mounts, with the tip slightly overhanging the front mount.
6.	Connect the Arduino to the computer and open the Arduino file.
7.	Enter the syringe diameter (mm) under “syringeDiameter” and the desired flow rate (mL/min) under “flowRate.
8.	Upload the code and confirm the upload is successful.
9.	Disconnect the Arduino from the computer and plug the power supply into an outlet. The LED should turn on.
10.	Press the red button to start the motor. The LED should turn green as the carriage presses the syringe.
11.	Press the red button again to pause. A yellow LED indicates the device is paused.
12.	When the carriage reaches the limit switch, the device will stop and the LED will turn red.
13.	To run another syringe, unplug the power, remove the syringe, reset the carriage using the lead screw, and repeat the process.
14.	When finished, unplug all cables and store the device in a safe, dry location.


{% include gallery caption="This is a sample gallery to go along with this case study." %}
