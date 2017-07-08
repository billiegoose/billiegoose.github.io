<!--
title: Javascript CNC Machine Emulator
-->
# Javascript CNC Machine Emulator

The University of Cincinnati's Robotics Team had a DYNA MYTE 2400 CNC machine sitting in its lab for several years. After sitting unused for many years, someone found the manual and I quickly made it my project to learn how to use it. During my time in California, I developed an urge to send a unique kind of postcard to my friends at the Robotics Team at UC - a CNC-it-yourself postcard. Having written a report on CNC machines comparing G-code with the native language of the DYNA MYTE 2400 the previous quarter, I knew the basic commands by heart (and could reference the manual for the rest). After coming up with my design for the postcard and writing out the code I thought would produce it, I decided I needed some way to test it before I sent it to the team. So I spent a couple of nights learning how to use the HTML5 `<canvas>` element and made a quick 2D emulator to parse my DYNA MYTE code and render it.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZL0pXrBJSBo" frameborder="0" allowfullscreen></iframe>

*Video demonstrating my Javascript emulator of the lab's CNC machine*

I sent them the code, and a link to this YouTube video to encourage them to machine the postcard. However, no one understood the machine as well as I did, and they weren't able to get the code entered while I was in California. It wasn't until I returned and entered the code myself that the postcard became a physical reality.

You can try the emulator yourself here: [CNC_Simulator.html](CNC_Simulator) It is just an HTML page with the Javascript source code embedded and no external references. Here are some sample CNC programs you can try:

- [CNC_Spiral.txt](CNC_Spiral.txt) - A simple example
- [CNC_D-SUB_PROGRAM.txt](CNC_D-SUB_PROGRAM.txt) - A program for cutting D-SUB sockets in sheet metal, which was the first use of the machine for the robotics team.
- [CNC_California.txt](CNC_California.txt) - The program seen in the video above.
- [CNC_California_Subs.txt](CNC_California_Subs.txt) - The same program, but using subroutines.
- [CNC_UC_Logo.txt](CNC_UC_Logo.txt) - A program for cutting the UC logo into sheet metal. (Note that UC's Logo is subject to regulations and shouldn't be used without permission.)

*Note*: You will have to change the Pixels per Inch setting based on your monitor to scale the image if it doesn't fit.