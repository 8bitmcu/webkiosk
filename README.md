webkiosk
========


One liner
----------------
`sudo apt-get install chromium-browser xorg && xinit /usr/bin/chromium-browser --kiosk www.google.ca %U - :1`


Install
-------
`sudo apt-get install chromium-browser`


Config
------
`which chromium-browser`

`sudo nano ~/.config/chromium/Default/Preferences`

(set resolution, fullscreen)

`sudo chmod 0400 ~/.config/chromium/Default/Preferences`


Use
---
`xinit /usr/bin/chromium-browser %U - :1`
