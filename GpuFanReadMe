*Written by Bong McPuffin* --- Last Tested Jan 2, 2019 on Linux Mint 19.1

This script allows for dynamic control of the GPU Fan Speed based on temperature.

Open nvidia-settings and click X Server Display Configuration and at the bottom click Save to Xorg Configuration File.

Then "sudo nano /etc/X11/xorg.conf" and add "coolbits=4" at the end of the [DEVICE] section, save. 

This enables fan control on the GPU in the nvidia-settings thermal settings menu. 

Then download and extract the gpufan.sh script somewhere such as /home/GPUFan.

Next go to Preferences -> Startup Applications -> at the bottom click the + button and then custom command, give this a name like GPU Fan Controller and then browse to where you placed the gpufan.sh script and select it. 

Reboot to have a dynamically controlled fan. (Make back ups of everything and closely monitor your temperatures in case you have to revert back)

IMPORTANT: You can alter the values in this script to suit your particular needs, just like in MSI Afterburner setting a fan curve.
