# PiCase

This is a case for the Raspberry Pi 5 that I made to learn how to use FreeCAD. This case will very likely not actually protect your pi, so use at your own risk. All screws used in this are M2x6.

## Mk1 Print

<img src="/img/mk1/mk1-inside.jpg" alt="inside view" width=200> <img src="/img/mk1/mk1-top.jpg" alt="top view" width=200> <img src="/img/mk1/mk1-side.jpg" alt="side view" width=200> <img src="/img/mk1/mk1-back.jpg" alt="back view" width=200>


The first attempt at modeling the case went better than I expected. The Pi fit snugly into the case, the hole for the ethernet and USB ports was perfect, the stilts the board sat on were of a resonable size relative to the case, and the ventilation pockets were perfect. Unfortunately several 
things were wrong with this first model. Every screwhole in the body of the case was too small and the screwholes in the lid did not allow free motion of the screw. I also forgot to account for the thickness of the PCB when making the pocket for the USBC and microHDMI ports, resulting in the 
entire PCB not aligning with it's screwholes. Finally, the pocket for the microSD card and power button did not have enough clearence for my stubby fingers to access either of them.

## Screw Test

<img src="/img/ScrewTest.jpg" alt="screw test" width=300>

The first problem I needed to solve was the size of the screw holes, so I printed a block with a bunch of unthreaded holes in it. I found that 2.1mm holes provided a very snug fit when the screw was wedged in and that the M2 option in FreeCAD allowed the screw to pass through without much resistance,
so I chose those for the diameter of the body and lid holes respectively.

## Mk2 Print

<img src="/img/mk2/mk2-inside.jpg" alt="inside view" width=200> <img src="/img/mk2/mk2-top.jpg" alt="top view" width=200> <img src="/img/mk2/mk2-back.jpg" alt="back view" width=200> <img src="/img/mk2/mk2-bottom.jpg" alt="bottom view" width=200>

Along with the changes to the screw holes, I made the pocket for the USBC and microHDMI ports taller, carved out a new pocket for the SD card that actually allowed my fingers to get inside, carved a divot into the bottom vent for power button access, and lowered the top of the body by 5mm.
These changes resulted in a snug fit for both the pi and the screws. While this version was huge improvement and was actually useable, there were still some issues. The 1mm fillet on the lid caused the screw holes in the lid to require wedging, the power button is *really* hard to access,
and the pocket for the USBC and microHDMI ports could stand to be a few millimeters wider to accound for wide cords. Overall, this print was a success and it will likely be the basis for my Pi powered cyberdeck.

## Mk3 Model

<img src="/img/mk3/mk3-1.png" alt="mk3" width=400> <img src="/img/mk3/mk3-2.png" alt="mk3" width=400>

I did not print this one as I don't actually plan on using this case, but I made a few changes to fix the problems present in the Mk2 print. I made the long sides of the walls 5mm thick instead of 3mm, raised the back vents, enlarged the power button pocket, and redesigned the lid to accomodate the body's new dimensions. Overall, I am very happy with how well this turned out for my first time designing and printing something.
