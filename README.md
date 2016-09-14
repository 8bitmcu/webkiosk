Webkiosk
========
This is a quick Chromium-based webkiosk for HTML applications

Install
-------
`sudo apt-get install chromium-browser`

Config
------
`which chromium-browser`

`sudo nano ~/.config/chromium/Default/Preferences`

(set resolution, fullscreen)

`sudo chmod 0400 ~/.config/chromium/Default/Preferences`


Usage
-----
`xinit /usr/bin/chromium-browser --kiosk www.google.ca %U - :1`
