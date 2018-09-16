# Software toolbox
When you want to use a 3D printer to print your own designs, you need to have
a few pieces of software. This guide contains the software that we use to make
our own designs.

## Design software
We use Fusion 360 for our designs. It has a steep learning curve for sure, but
it is one of the best pieces of design software around. Especially for designing
parts, which we do the most.

### Get the software
You can download the software here: https://www.autodesk.com/products/fusion-360/

Don't be fooled by the pricing information. Fusion 360 is free for students, 
teachers, educators and amateur makers. 

When you start the software you get a bar at the top of the window, telling you
that you have a trial version. Click this bar and request a license. 

In the license wizard, indicate whether you're a student, teacher, educator or
use the software at home. This will reduce the price to zero!

### Learn more about fusion 360
You can learn a lot from different youtube videos and the fusion 360 website.
But if you have money to spend or have a pluralsight subscription already, you 
can learn more about fusion in the 
[Fusion 360 learning path](https://app.pluralsight.com/paths/skills/fusion-360-core-skills).

## Slicer software
Apart from design software you need to have a piece of software called a slicer.
This will convert the 3D model into gcode, which is a language to express tool paths
for your 3D printer.

We use Cura from ultimaker as our slicer software. Some people prefer to use
a slightly older version of this software, but we opted for the latest-greatest.
Especially since we just started out printing parts.

## Get the software
You can download Cura from the ultimaker website: https://ultimaker.com/en/products/ultimaker-cura-software

## Configuration
In the cura software you need to setup your printer. We used these settings to configure our printer:

 - Machine Width (X): 305
 - Machine Depth (Y): 230
 - Machine Height (Z): 305
 - Nozzle Size: 0.4
 - Heated bed: Yes
 - Bed Center is 0,0,0: No

We then cutomized the bed temperature to 60 degrees celcius. 
So far this gives us great bed adhesion.