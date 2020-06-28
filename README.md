# Snackboard µX - A DIY audio mixer for deej
![Snackboard photo](/docs/top_view_photo.jpg)

## Description
This board uses 4 faders to control the volume of individual applications on Linux/Windows using [deej](https://github.com/omriharel/deej). 
I wanted to create a case for the Sliders, but without using a 3D printer or other tools. PCB manufacturing is pretty cheap nowadays so I wanted to try it.
My design uses both sides of the PCB, one for mounting the components and the other side for the design. The faders are sandwiched between two PCBs.

## Specifications
- 90 x 85 x 12 mm
- 4 sliders
- powered via Micro-USB
- [deej](https://github.com/omriharel/deej)

## Parts
- 1x Arduino (Pro) Micro
- 4x 75mm 10kOhm linear Slide Potentiometer (I used cheap ones from ebay with the part number B103)
- 4x M3 bolts
- 4x M3 nuts
- 4x 10mm spacers (you can use more nuts if you want)

## Usage
Just submit the files in /gerber/ to your preferred PCB manufacturer. (Most manufacturers prefer a .zip archive of these files.)

## More
If you need more faders you can check out [Snackya](https://github.com/Snackya/Snackboard-mix), his design uses 6 faders instead of 4.
