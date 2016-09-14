Webkiosk
========
This is a quick Chromium-based webkiosk for HTML applications.

Instructions included for Debian-based systems


Install
-------
`sudo apt-get install chromium`


Config
------
`which chromium`

`sudo nano ~/.config/chromium/Default/Preferences`

(set resolution, fullscreen)

`sudo chmod 0400 ~/.config/chromium/Default/Preferences`


Usage
-----
`xinit /usr/bin/chromium --kiosk www.google.ca %U - :1`
