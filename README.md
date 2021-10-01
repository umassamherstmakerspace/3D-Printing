# 3D Printer Introduction and Tutorial (UMass Amherst Makerspace)

<h3>
Getting started with Cura
</h3>

This is your tutorial on how to print here at the makerspace..
BE SURE TO PAY ATTENTION!

Cura is a powerful slicer we use at the makerspace, so lets get started.

**IF using your own device, follow this short paragraph below, if not skip it**
First, download cura:

https://ultimaker.com/software/ultimaker-cura 

For some of our printers, like the Creality Ender 3, profiles are quite simple to obtain
while for some other machines, you will have to follow a tutorial in order to be able to get printing.

 <a href="https://github.com/umassamherstmakerspace/3D-Printing#creality-ender-3-pro">Ender 3 Pro</a> 
 <a href="https://github.com/umassamherstmakerspace/3D-Printing#creality-cr-6-max">Creality CR-6 Max</a> 

<h4>
Adjusting your print settings
</h4>
Adjusting your print settings can be quite a daunting task, and always feel free to ask makerspace staff with help on how to get the right settings, but here's a general overview to get you going.

First, select the profile settings box under marketplace and signin at the top right, and click custom at the bottom right of it, select the profiles drop down and make sure you have a CUSTOM PROFILE selected, any profile imported will be in that section.

1) Print Types

*High Detail and Small*
Speed: High detail prints should be printed in lower layer heights, anywhere from .12,.16 or .2 is optimal, and usually the smaller the piece is, the smaller the layer height, so highly detailed and larger would be .2, while really small and detailed .12.
Material: With high detailed prints, you should usually be printing in PLA or Pro PLA, and on the lower side (usually 200C, 210-220C Pro PLA/PLA+)
Support: Make sure support interface is off when printing with complex overhangs and complex supports, and generally you want your support density to be around 18-25% with high detailed parts (depending on how much support you need). To disable support interface, go to the profiles search, search interface, drop down the supports box and make sure "Enable support interface" is unchecked.

*Draft/Low Detail*
*to be continuted*

<h4>
Creality Ender 3 Pro
</h4>
**CURA SETUP ON PERSONAL DEVICE**

*Feel free to let staff know if you need help with setup*

When downloading cura and in setup for the first time, select printer type as Non-Networked printer > Creality Ender 3 Pro.
If cura is already downloaded, go to Preferences > Configure Cura > Printers > Add > Add a Non-Networked printer > Creality > Creality Ender 3 Pro

*Please Note*: While cura profiles for the Ender 3 are fine, we have our own files that are made to be imported into cura. 

1) At the top of the github, select code and then download zip, open the zip folder, go into the Ender 3 Pro folder, and move the profile(s) into your downloads folder. 

2) Open Cura, Go to Preferences > Configure Cura > Profiles > Import
Then select the profile you'd like to import. Do the same for any other profiles for the Ender 3 Pro.

3) Import your 3D file into Cura by clicking the folder icon in the top left, and now we'll get into tweaking.

4) Now you're all set, go back up to the cura section by scrolling or clicking <a href="https://github.com/umassamherstmakerspace/3D-Printing#getting-started-with-cura">here</a> and read on how to adjust your print settings.


<h4>
Creality CR-6 Max
</h4>
**CURA SETUP ON PERSONAL DEVICE**

*Feel free to let staff know if you need help with setup*

When downloading cura and in setup for the first time, select printer type as Non-Networked printer > Creality Ender 3 Pro.
If cura is already downloaded, go to Preferences > Configure Cura > Printers > Add > Add a Non-Networked printer > Creality > Creality Cr-6 SE THEN follow the next instructions to adjust for the Creality CR-6 Max

1) Under Printer settings, change the X, Y and Z depth to 400mm, then under start-gcode, look for the G28 command.

2) Right under the G28 command, copy and paste this: M420 S1; Retrieve Bed level
G29 O; Verify Bed level retrieved

3) Click "Close".

*Please Note*: You must import our Creality CR-6 Max Profile(s) in Cura in order to print.

1) At the top of the github, select code and then download zip, open the zip folder, go into the Creality CR-6 Max folder, and move the profile(s) into your downloads folder. 

2) Open Cura, Go to Preferences > Configure Cura > Profiles > Import
Then select the profile you'd like to import. Do the same for any other profiles for the Creality CR-6 Pro.

3) Import your 3D file into Cura by clicking the folder icon in the top left, and now we'll get into tweaking.

4) Now you're all set, go back up to the cura section by scrolling or clicking <a href="https://github.com/umassamherstmakerspace/3D-Printing#getting-started-with-cura">here</a> and read on how to adjust your print settings.