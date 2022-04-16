# Raspberry Pi USB Gadget setup script

This script takes a Raspberry Pi already setup for remote access via SSH or VNC and enables USB On-The-Go (OTG) functionality (currently tested and working on Raspbian Bullseye). USB OTG enables the device to be plugged into a USB port, powered and directly accessed over IP from the host computer without any other network access.  

The script and code are based on an original blog post by [Ben Hardill](https://www.hardill.me.uk/wordpress/2019/11/02/pi4-usb-c-gadget/), with additional code from [Tech Craft](https://github.com/techcraftco/rpi-usb-gadget/) to enable the service through systemd. Pre-built Raspbian images with USB OTG enabled can also be found [here](https://github.com/techcraftco/rpi-usb-gadget/releases).  

