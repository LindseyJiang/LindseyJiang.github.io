---
title: "Multimaterial Pliers"
excerpt: "Parallel-action needle nose pliers capable of gripping and picking up through-hole resistors. The model is multi-material printed using two different filaments: PLA and TPU (90A)."

header:
  image: /assets/img/picking_up_resistor.gif
  teaser: /assets/img/plier.png

gallery1:
  - url: /assets/img/spring_1.jpeg
    image_path: /assets/img/spring_1.jpeg
    alt: "Image 1"

  - url: /assets/img/spring_2.jpeg
    image_path: /assets/img/spring_2.jpeg
    alt: "Image 2"

  - url: /assets/img/spring_3.jpeg
    image_path: /assets/img/spring_3.jpeg
    alt: "Image 3"

gallery2:
  - url: /assets/img/demo_back.gif
    image_path: /assets/img/demo_back.gif
    alt: "Image 4"

  - url: /assets/img/demo_front.gif
    image_path: /assets/img/demo_front.gif
    alt: "Image 5"

  - url: /assets/img/demo_side.gif
    image_path: /assets/img/demo_side.gif
    alt: "Image 6"


---

The goal of this project was to design and print needle nose pliers capable of gripping and picking up through-hole resistors. The model is multi-material printed using two different filaments: PLA and TPU (90A). The TPU part functions as a “spring” to push the PLA parts apart from each other in resting position. Compression force is used to bring the plier’s jaws together. 
The model was originally designed to be print-in-place, meaning that they should not require any assembly post-print. With the elimination of screws, pins, fasteners, adhesives, and other assembly hardware, print-in-place models save a significant amount of time. Chains, which are usually linked one by one, can be printed quickly all at once (example [here](https://www.thingiverse.com/thing:2916907)). Another example would be a ball joint (example [here](https://www.thingiverse.com/thing:454814) which would otherwise be much more difficult to assemble.

## About the Design Process 
#### PLA Parts 

<div style="text-align: center;">
  <img src="/assets/img/pliers_1_and_2" alt="Plier PLA part iterations images" width="60%">
</div>
I aimed to design the pliers as small as possible for transportability and fast printing time. Larger models were also on the less precise end when I tested previously printed pliers. A tolerance of 0.3 mm was used throughout the entire final design.     
The specific type of pliers I chose were parallel action pliers, which constrain the movement of the plier’s jaws to remain in parallel. Most other pliers have only a single point of contact while parallel action pliers ensure that the entire face of the jaw comes in contact upon closure. 
In the first design of the pliers (white model) the three fasteners snapped when I tried to remove the supports. I increased the thickness of all the parts as well as the clearances for the second iteration (black model). The same issue occurred again. Given time constraints, I ultimately resorted to using M2 x 12 screws with nuts to hold the pieces together, deeming the pliers no longer a print-in-place model. The torsion applied by the rotations of the handles onto the hinges was too great for a 2 mm diameter PLA piece, especially since they were printed along the X-Y plane.  

#### TPU Parts 
In terms of materials, 90A was selected over 95A for more flexibility. To test different resistances of the spring component, three infill percentages were used: 35%, 30%, and 25% (from left to right). This was done for all three iterations of the spring components. 

The first iteration of the spring component was meant to connect to the other ends of the jaw parts, shown below in the gallery. The two protruding bits would create a dove-tail shaped connection between the two jaw segments. Given the small size of the pliers, however, the connection points (originally designed to be 1.5 mm wide) failed to print to the resolution required to actually create a rigid joint. When I used my hands to squeeze down on the spring component, it also flexed significantly out of plane, and it could be seen that this flexion could not be accommodated by the plier design. Much of this flex appeared to be due to the large height compared to width of the component. 

I then decided to use a design that was wider than it was tall, which worked much better. I also changed the connection mechanism to lay within the insides of the handles. The dovetail would slide into a cut made in either of the handles from the end. This design was much more successful and allowed for larger cuts to be made as the handles are the thickest part of my design. It is shown below. 

<div style="text-align: center;">
  <img src="/assets/img/dove_tail" alt="TPU to PLA connection image" width="60%">
</div>

After the second iteration, I quickly realized that the component was not tall enough to push the jaws away from each other. I then made the ovals taller and wider, which pushed the jaws apart better. 

{% include gallery id="gallery1" layout="third" %}
**First, second, and third iterations of spring component (left to right)**

## Specifications 
#### Jaw measurements 
The jaw is approximately 15 mm long, and can open up to 6.5 mm. The entire plier is roughly 130 mm long when resting. 

#### Print Settings
| Setting          | PLA      |TPU      | 
| ------------- |:-------------:|:-------------:|
| Print width (mm) | 0.4 | 0.6 |
| Bed temperature (°C) | 65 | 60 |
| Print temperature (°C) | 215 | 240 |
| Bottom and top solid layers | 3 | 0 |
| Infill (%) | 20 | 25 |
| Infill pattern | Gyroid | Grid |

## CAD Model 
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811705aeb8185a93df8?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


{% include galleryd id="gallery2" layout="third" %}
**Demonstration of plier from different angles" 
