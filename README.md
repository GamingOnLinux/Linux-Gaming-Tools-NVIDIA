# Conky-Toggle

*Written by Bong McPuffin* - - - 
*Last tested on January 2nd, 2019.*

This script toggles Conky's above/below line (makes it always stay on top of other windows or pushes it to background).

THIS SCRIPT ASSUMES CONKY IS ALREADY RUNNING! MAKE SURE CONKY HAS BEEN STARTED!

Download into ~/.conky/Toggle or some place sensible (doesn't really matter where).

IMPORTANT: Edit the /home/CHANGEUSER/.conky/GameMonitor/conkyrc line to reflect your user name or this script won't work! If you install your conky themes somewhere else then you will need to include the full path to that directory.

Add to Keyboard Shortcuts by going to Preferences -> Keyboard -> Shortcuts -> Add custom shortcut.

Name it "Conky A/B Toggle" or something similar -> Click the button next to the Command field and navigate to where ever you unzipped this file this file.

Next click on Custom Shortcuts in the left side window and click Conky A/B Toggle or whatever you named it then down below click on  one of the "unassigned" slots and then put your desired key or key-combo in there.

Congrats, you can now toggle Conky to be above all other windows or push it to the background at will without having to open a text editor!

Highly recommended for those with nVidia cards: Open nvidia-settings and click X Server Display Configuration and at the bottom click Save to Xorg Configuration File and then "sudo nano /etc/X11/xorg.conf" and add "coolbits=4" at the end of the [DEVICE] section. This enables fan control on the GPU. Then download and extract the gpufan.sh script somewhere such as /home/GPUFan. Next go to Preferences -> Startup Applications -> at the bottom click the + button and then custom command, give this a name like GPU Fan Controller and then browse to where you placed the gpufan.sh script and select it. Reboot to have a dynamically controlled fan. (Make back ups of everything and closely monitor your temperatures in case you have to revert back)

Optional (but recommended): Pair this script up with the custom conkyrc file provided. Place the conkyrc into ~/.conky/GamingMonitor and run with ConkyMananger2. This conkyrc displays the time, CPU temp, and GPU temp.

Instructions for installing ConkyManager2 here (works with Ubuntu 18.04/Linux Mint 19.*)  -> https://github.com/zcot/conky-manager2/blob/add-1.10-support/HOWTOBUILD.md
