# Leveling guide
The CR-10 mini doesn't feature automatic leveling, although you can add it by 
building your own. We've not done that yet, so we wrote a guide to help 
ourselves level the printerbed on this printer.

## Step 1: Prepare the printer
Before you start leveling the printer, make sure that it is on a level surface. 
Also make sure that the printerbed is clean, nothing worse than collecting 
debris or dust while leveling.

You need a preheated bed, so that all materials that normally expand when 
heated, are expanded to the correct size. We used to level without doing this, 
but learned that it helps to get a better leveling result.

Execute the following steps to preheat the bed:

 - Select `Control`
 - Select `Temperature`
 - Set bed temperature to 45 degrees celcius

Once you've preheated the bed, execute the following steps to reset the axes 
of the printer to their default positions.

 - Select `Prepare`
 - Select `Autohome`

With the printer in the home position, disable the steppers using these steps:

 - Select `Prepare`
 - Select `Disable steppers`

## Step 2: Level the four corners of the printerbed
There are four leveling knobs underneath the printerbed, you can use these to 
level the printerbed. The goal is to have a distance of 0.1 mm between the 
printhead and the printerbed. This happens to be 0.1 mm.

So in order to level the bed, repeat the following process for each of the 
four corners:

 - Move the printhead the x and y axes to the corner you want to level.
 - Stick a post-it between the printhead and the bed
 - Adjust the leveling knob so that the printhead bearly catches on the post-it.

**Note:** The paper should just catch on the head, but you should be able to 
slide away from the head with some effort. If the paper tears it is clearly too 
close. If it slides without any resistance, the printerhead is too far away 
from the bed.

Alternatively you can use 0.1 mm feelergages, which are normally used to gap 
in sparkplugs. We haven't used those, because the post-it trick works great.

## Tips and tricks

### Replace the standard leveling knobs
The standard leveling knobs on the CR-10 mini are pretty small. I personally was
unable to adjust the level using these knobs because of a lack of dexterity in 
my hands. 

We printed an uprade for our printer to make it easier to adjust the bed level.
[The ultimate leveling knobs](https://www.thingiverse.com/thing:2408748/)
upgrade can be dowlnoaded for free from thingyverse. 


