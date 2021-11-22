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

<h3>
Preparing Cura on your device
</h3>
Adjusting your print settings can be quite a daunting task, and always feel free to ask makerspace staff with help on how to get the right settings, but here's a general overview to get you going.

First, select the profile settings box under marketplace and signin at the top right, and click custom at the bottom right of it, select the profiles drop down and make sure you have a CUSTOM PROFILE selected, any profile imported will be in that section.

Under Print settings and Profiles you'll see an icon with 3 lines, click that dropdown and select "Expert" this will ensure you have all settings available for modification.

Each dropdown contains settings to adjust for each specific category. For example, to adjust infill percentage you would dropdown infill and change percentage and/or pattern.

If you have any questions about navigating settings, let Makerspace staff know so we can help.

<h3>
Adjusting settings for your prints
</h3>

<h4>
Quality
</h4>
Only thing to modify here is layer height. The Z-axis motors operate in steps of .04mm, so best layer heights are multiples or half steps of that. 0.2 is most common and is usually good for most things. For large parts, use .28 or .3, and for very small or detailed parts .12 is best. Remember, going small only makes the print take longer and can actually reduce strength.

<h4>
Infill
</h4>
Stick to modifying Infill Density, Grid pattern usually has the most efficient time-strength ratio. For most parts, 15-20% is more than enough infill. For parts that really experience no strain like a figure, stick to 15%, if your part experiences moderate strain, 20% should be good. If you think you might need more than 20%, run it by Makerspace Staff.

<h4>
Material
</h4>
Each filament has its own range of temperatures to print at. There are profiles that are setup for specific filaments, listed below are the temp ranges they should be at for reference.<br>
<br>
<ol>
<li><b>HD</b>:<br>
HD consists of PLA filament
Nozzle
PLA 200-210C. Pro PLA 220-230C
Bed
All PLA 60C</li>
<li><b>PETG</b>:
Nozzle
PETG 240-250C
Bed
PETG 80-90C</li>
</ol>
<h4>
Supports
</h4>
Here comes perhaps the most important part of 3D printing. Supports can make or break your print. Our profiles are fined tuned for easy to remove supports that both support the part and allow for efficient removal.<br>
<br>
<b>Interface</b>
<br>
Most of the time, you'll only be chosing whether or not you want interface on or off. Interface allows for very smooth surfaces, but can be hard to remove with very complex and hidden overhangs. if you have simple 90 degree or very agressive and accessible overhangs, support interface allow for even better and cleaner surfaces. To enable or disable support interface, simply search interface and go to the supports dropdown to enable or disable them (interface will only appear if supports are enabled.)<br>
<br>
<b>Support Density</b><br>
The best support density is usually 18%. This is a great balance between quality and efficient removal. For really large parts, 15% with interface might be easier to remove and will print really well if the overhangs are simple. If parts are really tiny, 20% supports can help slightly, but will be harder to remove.

<h4>
Build Plate Adhesion
</h4>
Skirt is great for most parts, if you have very complex bases, brim should be more than enough. Raft is never needed if the printer is working correctly.

<h4>
All Other Dropdowns
</h4>
These can be ignored, unless otherwise told to be modified by Makerspace Staff.

<h3>
Creality Ender 3 Pro
</h3>
**CURA SETUP ON PERSONAL DEVICE**

<i>Feel free to let staff know if you need help with setup</i>

When downloading cura and in setup for the first time, select printer type as Non-Networked printer > Creality Ender 3 Pro.
If cura is already downloaded, go to Preferences > Configure Cura > Printers > Add > Add a Non-Networked printer > Creality > Creality Ender 3 Pro

*Please Note*: While cura profiles for the Ender 3 are fine, we have our own files that are made to be imported into cura. 

1) At the top of the github, select code and then download zip, open the zip folder, go into the Ender 3 Pro folder, and move the profile(s) into your downloads folder. 

2) Open Cura, Go to Preferences > Configure Cura > Profiles > Import
Then select the profile you'd like to import. Do the same for any other profiles for the Ender 3 Pro.

3) Import your 3D file into Cura by clicking the folder icon in the top left, and now we'll get into tweaking.

4) Now you're all set, go back up to the cura section by scrolling or clicking <a href="https://github.com/umassamherstmakerspace/3D-Printing#getting-started-with-cura">here</a> and read on how to adjust your print settings.


<h3>
Creality CR-6 Max
</h3>
**CURA SETUP ON PERSONAL DEVICE**

<i>Feel free to let staff know if you need help with setup</i>

When downloading cura and in setup for the first time, select printer type as Non-Networked printer > Creality Ender 3 Pro.
If cura is already downloaded, go to Preferences > Configure Cura > Printers > Add > Add a Non-Networked printer > Creality > Creality Cr-6 SE THEN follow the next instructions to adjust for the Creality CR-6 Max

1) Under Printer settings, change the X, Y and Z depth to 400mm, then under start-gcode, look for the G28 command.

2) Right under the G28 command, copy and paste this: 

M420 S1; Retrieve Bed level

G29 O; Verify Bed level retrieved

3) Click "Close".

*Please Note*: You must import our Creality CR-6 Max Profile(s) in Cura in order to print.

1) At the top of the github, select code and then download zip, open the zip folder, go into the Creality CR-6 Max folder, and move the profile(s) into your downloads folder. 

2) Open Cura, Go to Preferences > Configure Cura > Profiles > Import
Then select the profile you'd like to import. Do the same for any other profiles for the Creality CR-6 Pro.

3) Import your 3D file into Cura by clicking the folder icon in the top left, and now we'll get into tweaking.

4) Now you're all set, go back up to the cura section by scrolling or clicking <a href="https://github.com/umassamherstmakerspace/3D-Printing#getting-started-with-cura">here</a> and read on how to adjust your print settings.