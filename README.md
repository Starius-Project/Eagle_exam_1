# MX Key PCB

This is your first PCB Designer Exam, so we'll keep it simple.

You will create a simple PCB with 3 MX Key (mechanical Keyboard) and an USB connector to connect to the PC and have programmable shortcut key.

For the exam you have access to Internet and [Wiki](https://github.com/iutlongwy/Eagle/wiki/Home) from IUT LONGWY GITHUB, [Library](https://github.com/Starius-Project/Eagle_examen_1/tree/master/eagle/Lib) (follow the Wiki for instructions) and Drawing.

**Don't forget to make a Document (in French) to explain all the steps of the Design, I will use this document and the Eagle files to rate you. So keep it clear and complete.**

**Send everything in a .RAR file at captant.mickael@gmail.com BEFORE the end of the exam**

You have 4 hours, good luck !

## Dimensions

![Screenshot](https://github.com/Starius-Project/Eagle_examen_1/blob/master/docs/drawing_screenshot.jpg)

All dimensions are in mm.

You need to respect the position of CHERRY MX KEY and USB.

Add 4 holes on the side for M3 screws.



## Components

To make this design you need the following components:
- [CHERRY-MX-LED](https://be.farnell.com/fr-BE/cherry/mx1a-11nw/switch-tactile-spst-no-0-01a-tht/dp/2292961) from cherry MX library 
- ATMEGA32U4 from Adafruit library
- all the necessary components around (only use 0805 components for resistors and capacitors)
- USBMINIB from Adafruit library

## Different Steps

you must validate the different steps by calling the teacher before continuing the following tasks:

- find components and place on the schematic
- Connect them with Net and Net Name
- synchronize with the PCB
- change dimensions of the PCB (based on drawing)
- place main components on the PCB (USB, Cherry Key, ATMEGA based on drawing)
- place other components
- route tracks and place VIA for GND + place GND Polygon (one BOTTOM and one TOP)
- place Serigraphy
- Send files


