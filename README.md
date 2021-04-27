# Tor-Browser-Pinephone (and other Linux Phones- should work on Librem5 but I do not have access to check)
Setting up Tor Browser port + adding button to Phosh/Linux phones

I just finished 2 videos: one showing Tor Browser bundle ported to Arm64 on Pinephone + Pinetab. Running Mobian and Arch but should work for any Linux phone using Phosh (replace the desktop file information if you do not use phosh to match your current interface).

Video showing what Tor Browser on your Linux phone looks like: https://odysee.com/@RTP:9/privacy-tor-browser-on-pinephone-pinetab:3

INSTRUCTIONS:

1.) Download the required Arm64 Tor Browser port from here:

https://sourceforge.net/projects/tor-browser-ports/files/

2.) 
***Video Tutorial: How to Add Tor Browser to Phosh Desktop: https://youtu.be/vtdtCVL51Bo

For Arch and most other distros, following the above video will leave you with a working Tor Browser Icon/button on your phone's desktop.

For Mobian, the same video/steps apply, but-- to have a working Tor Browser button you will need to replace the start-tor-browser.desktop file's 'Exec=' line with:

    Exec=/bin/bash /home/mobian/tor-browser_en-US/Browser/start-tor-browser --detach

Make sure to Like, Share and Subscribe to show your support for more content like this.

Support/Blog: https://www.buymeacoffee.com/politictech

I appreciate it. :)

------------------------------------

Official Tor Project website: www.torproject.org (I have no relation to the Tor Project, just trying to help fellow Linux Phone users and appreciate Tor)

