# Author
Author: Daechir <br/>
Author URL: https://github.com/daechir <br/>
License: GNU GPL <br/>
Modified Date: 08/01/21 <br/>
Version: v1a


## Purpose
Transcendence serves as a minimal SDDM theme adhering to the KISS principle. <br/>
This theme was built on Arch Linux and tested on Lubuntu 21.04 as of the listed modified date. <br/>

## Options
Out of the box Transcendence supports five options:
+ displayHeight=1920
+ displayWidth=1080
+ displayFont="Ubuntu"
+ displayFontSize=14
+ background=images/background.jpg

For the best results and performance make sure to add your display dimensions. <br/>
As always you may change the default options to your specifications in theme.conf.


## Installation
Installing this theme is as simple as it gets. <br/>

### Lubuntu 21.04:
`curl -o sddm-transcendence.zip https://codeload.github.com/daechir/sddm-transcendence/zip/v1a` <br/>
`unzip sddm-transcendence.zip` <br/>
`mv sddm-transcendence-1a Transcendence` <br/>
`sudo cp -R Transcendence /usr/share/sddm/themes/` <br/>
`sudo chmod -R 755 /usr/share/sddm/themes/Transcendence/` <br/>
`echo -e "[Theme]\nCurrent=Transcendence" | sudo tee -a /etc/sddm.conf > /dev/null` <br/>
  
If you're missing curl install it with sudo apt install curl.

