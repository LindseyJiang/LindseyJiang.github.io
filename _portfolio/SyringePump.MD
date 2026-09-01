---
title: "Syringe Pump"
excerpt: "This design project used modern techniques of filament 3D printing and microcontroller programming to design a functional syringe pump."
header:
  image: /assets/img/Cyber-Scooter-Banner.jpg
  teaser: /assets/img/Cyber-Scooter-TH.jpg
gallery:
  - url: /assets/img/Cyber-Scooter-1.jpg
    image_path: assets/img/Cyber-Scooter-1.jpg
    alt: "placeholder image 1"
  - url: /assets/img/Cyber-Scooter-2.jpg
    image_path: assets/img/Cyber-Scooter-2.jpg
    alt: "placeholder image 2"
  - url: /assets/img/Cyber-Scooter-3.jpg
    image_path: assets/img/Cyber-Scooter-3.jpg
    alt: "placeholder image 3"
---

This design project used modern techniques of filament 3D printing and microcontroller programming to design a functional syringe pump. The project supports 20 mL and 10 mL syringes. Two syringe pump diameters were used to calculate maximum flow rates. A 14.3 mm diameter syringe’s maximum flow rate is 12.044 mL/min. A 19.2 mm diameter syringe would have a maximum flow rate of 21.713 mL/min. 

## 
| Name          | Quantity      | 
| ------------- |:-------------:| 
| Computer with USB port | 1 | 
| Arduino     | 1 |   
| Stepper motor | 1 |    


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
