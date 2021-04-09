# VSD-Sky130-OpenLane-Workshop

This is my github repository for the VSD Sky130 OpenLane workshop
during April 2021. (this line added from inside lab instance computer)

Next added by pasting screenshot into github.com editor:
![image](https://user-images.githubusercontent.com/272611/114073204-06ef3b00-9871-11eb-8d14-9c759115292a.png)


Day 1: Introductions to concepts and tools.
The PDK means Physical Design Kit, or alternatively Process Design Kit. I have also seen the term FDK, for Foundry Design Kit, but PDK is most common.
The Skywater 180nm PDK is not natively compatible with open-source EDA tools, and so needs to be converted to be useful to the opne-source tool set and flow used in this workshop. The open-pdks package is what is used to operate on the incompatible PDK delivery and generate a compatible version as output.

![image](https://user-images.githubusercontent.com/272611/114124088-9f151080-98c1-11eb-97bb-49b8f2d894b1.png)

In this listing, there are 3 directories about pdks. 
skywater-pdk - This directory holds the original PDK data as provided by the foundry, but is not compatible with these tools.
open_pdks - translation package to generate a compatible version of the PDK.
sky130A - translated and compatible version of the Skywater 130nm PDK content.

Here is our translated and compatible content structure:
![image](https://user-images.githubusercontent.com/272611/114124374-50b44180-98c2-11eb-8a21-16b2b05c0dae.png)

The instructional video about the first commands in the shell terminal window display a docker command that is not discussed, and it seems that in the current lab instance machines, the docker command is not known at all in the $path. So will assume safe to skip that...

I changed my shell prompt as it got very long after cd into the work area location. This lets us see my commands easier in screenshots, as the instructors want to see usernames to match to students, and we can do that without hte long current directory takign up so much space. The lab instance computer screen width is limited to much less than my laptop screen, so shorter is better.
![image](https://user-images.githubusercontent.com/272611/114125458-82c6a300-98c4-11eb-8580-74c93c0f20d6.png)


Now, to our first command... We will br running the OpenLane toolset in an interactive fashion for now, manually typing in commands to it at each step. After starting the flow script, we need to activate the openlane 0.9 package.
![image](https://user-images.githubusercontent.com/272611/114125647-e2bd4980-98c4-11eb-9150-14f9b908c647.png)

We will be operating on the picorv32a design for now.
![image](https://user-images.githubusercontent.com/272611/114126006-932b4d80-98c5-11eb-8a97-9702a0becdc7.png)







