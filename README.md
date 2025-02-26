# ThermalTake Tower 300 LCD Stuff
Here's some miscellaneous stuff for the ThermalTake Tower 300 PC Case. The lower cover, where a ThermalTake 3.9" can be placed, is replaced by a 7.84" LCD with mini HDMI interface. The HDMI cable can be connected as a secondary/tertiary/any display within Windows. You can run any tools or screen add-on on this display. In this example AIDA64 Extreme is used to display a Sensor Panel. This repository contains the information needed to create your own display.

![Tower 300 Sand&Gravel LCD](img/ThermalTakeTower300LCD.jpg)

### Case Modification
To fit the display pretty flush with the sides, you need to grind away the lower standing edge of the case. You can do this with a small grinder tool like a Dremel. Leave about 1 millimeter of the standing edge. After cutting, you also need to flatten the recess in the middle a little bit. Depending on the thickness of the connection on the LCD, you might also bend the left edge on the lower part of the metal. Keep the hole in place, it's needed for the frame. Be sure to remove all metal dust, it will be everywhere and might cause a short circuit if not cleaner well.
![Tower 300 Sand&Gravel LCD](img/LCDCutLowerEdge.jpg)

### The Display
The display used is a 7.84" 1280x400 pixels display from WaveShare. Bought from eBay, seller "BuyDisplay", but they're also available on Amazon and many other webshops. Just make sure its the 7.84" display and not the 8" display, the latter will not fit in the opening of the cover. Be careful with the FPC-cable, it's very fragile and any folding or scratching can cause permanent damage.
![Tower 300 Sand&Gravel LCD](img/LCDExampleBuyDisplay.jpg)

### The Frame
The frame is designed as two seperate parts, one is the front bezel and visible, the other part is a backpanel that fits the two holes and fixes the small PCB. It also provides two mounting point to fix the USB and Micr-HDMI cable to prevent the connectors ripping of the PCB. The 3D .stl files are in the folder "3D Files". Print them with 0.40mm nozzle and 0.20mm layer height, 100% infill. Depending on the printer you're using, supports might be needed.

When printed, screw the PCB into the supports using three 2.5x5mm screws. Be sure the tips of the screws stay withing the backplate, otherwise the tips might damage the display. Glue the LCD into the front bezel (although it might fit and stay without any glue). In the bezel there is a small cutout where the flatcable fits, this is the left side of the bezel, seen from the front side. Then glue or tape with double sided/carpet tape the backplate on the back of the LCD. The backplate should fit withint the edges of the bezel. Mount the FPC-cable on the LCD and PCB. Plug in the USB and Micro-HDMI cable. Fix the cable with tie-wraps to the two lugs. There should be no stress on the connectors.

Insert the entire assembly in place, the FPC-cable should be to the left, the USB and Micro-HDMI cables to the right. Easiest way to insert the assembly is to fit the two pins in the locking holes and the top edge of the bezel locked under the metal of the case. Then press the bottom into place. It is a tight fit, pulling back the bottom plate a bit might make it easier to snap in place. Do not press very hard on the LCD, this might damage your display.
![Tower 300 Sand&Gravel LCD](img/CADBezelBackDesign.jpg)

### AIDA64 Sensor Panel
In the AIDA64 folder are the files you need to use the sensor panel as a 400x1280px display. The fonts used are added as Windows TrueType fonts. The font Arial Nova can be installed from the Microsoft Store, just search for "Arial Nova" and install the font. The 7-Digit font can be installed by right-clicking on the file and choose "Install Font". Import the .panel file in the Sensor Panel Manager. Set the panel to the display number used, make it show always on top. Start AIDA64 on boot so it will start automatically and show the panel.

There are also seperate .png files. These are the image files for the orange backgrounds with several heights and the extra graphical bezels. These bezels consist of a top, center and bottom part, and several sides with a different height. By overlapping the images you can create nice bezels. See the example sensor panel.

Change the sensor data and layout to your likings. The example sensor panel is a work in progress and not the final version. Also, sensor data differs from brands of mainboards, graphic cards etc. On the forum of AIDA64 there a lots of other examples and ideas, see ![AIDA64 Share your Sensor panel](https://forums.aida64.com/topic/13296-share-your-sensorpanels/)


Enjoy and have fun, share your creations on the forum, Reddit or whatever.
