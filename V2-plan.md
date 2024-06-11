# Version 2 of BlueData

Written by Matt Gleich on 06/11/2024.

## Reflection

V1 of BlueData was a success but like any project there are areas that can definitely be improved upon. Due to some last minute technical difficulties, we had to abandon the Raspberry Pi platform and switch to using just an arduino. This switch introduced a host of problems and compromises, which definitely should be addressed in V2 of the project. The goal of V2 is to be better than V1 ever could've been even if the Raspberry Pi platform was supported.

### Physical Structure of System

One **major** problem with V1 of the system is that requires a lot of "loose" connections to make sure that everything works. This provides a lot of places for failure. If water was sprayed on the side of the boat and the system got even a little bit of water in it then everything could easily break. Providing a more minimal system that is easier to setup, has less failure points, and is more resilient to water or user-error should be the goals of V2 regarding the physical structure of the system.

### User Experience (UX)

Mr. Mailhot or someone would have to setup and run the arduino program on the Raspberry Pi and then open the console to show the incoming data. This is an extra complex setup in the setup process but also provides a very basic and unpleasant experience for the students collecting the data. If the system just needs to be powered on and then would provide a simple display for all the values that would make everything much easier to work with.

### Accuracy of sensors

There were some reports of some of the sensors not being very accurate. This should be looked at and improved as much as possible in V2 of the project.

## Proposal

I am proposing that we make a PCB (printed circuit board) that would precisely accomplish the goals of this project. This circuit board would have features such as:

- Clear and easy to work with displays for showing data
- Big ports for plugging in the sensors.
- Battery onboard

This should in theory provide a box that you can simply turn on, plug in the sensors, and get all of the data we need displayed on the box.

### Waterproofing

I want to bring on my good friend Hayden Smith to help with designing a case for this system. He has experience working with CAD and we could just have the case 3D printed.

### PCB design

I have a bunch of PCB design experience along with my other friend Niranth Chamarty. I would love to bring him on to help work on designing the board while I can spend more time focusing on the software.
