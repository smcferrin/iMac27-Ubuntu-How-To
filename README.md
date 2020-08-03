# Getting an iMac 27 Retina Running Ubuntu 20.04.1 LTS

### Mouse
Mousewheel 

https://dev.to/bbavouzet/ubuntu-20-04-mouse-scroll-wheel-speed-536o

Install imwheel

    sudo apt install imwheel

Install the mousewheel.sh file

Then 

    chmod +x mousewheel.sh
    ./mousewheel.sh

Finally add imwheel in ubuntu startup application.

### Sound 

in 
/etc/modprobe.d/alsa-base.conf

Add 'options snd-hda-intel model=imac27_122' to the end of the file. 


reboot or 

    sudo alsa force-reload

then run the mixer 

    alsamixer

Unmute the Headphone jack and set the sound levels. 

### iSight

https://help.ubuntu.com/community/MactelSupportTeam/AppleiSight?action=show&redirect=AppleiSight

