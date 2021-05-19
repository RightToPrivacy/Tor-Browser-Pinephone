# Tor-Browser-Pinephone (and other Linux Phones- should work on Librem5 but I do not have access to check)
Setting up Tor Browser port + adding button to Phosh/Linux phones

I just finished 2 videos: one showing Tor Browser bundle ported to Arm64 on Pinephone + Pinetab. Running Mobian and Arch but should work for any Linux phone using Phosh (replace the desktop file information if you do not use phosh to match your current interface).

Video showing what Tor Browser on your Linux phone looks like: https://odysee.com/@RTP:9/privacy-tor-browser-on-pinephone-pinetab:3

INSTRUCTIONS:

1.) Download required Arm64 Tor Browser port from here:

https://sourceforge.net/projects/tor-browser-ports/files/

2.) 
***Video Tutorial: How to Add Tor Browser to Phosh Desktop: https://youtu.be/vtdtCVL51Bo

### OR IF YOU WANT TO SKIP THE VIDEO, FOLLOW BELOW:

1.) Download Arm64 Tor Browser port:

https://sourceforge.net/projects/tor-browser-ports/files/

2.) Extract the Tor Arm64 Browser. 

3.) Save my edited (for Mobian fix) start-tor-browser.desktop file to:
    /usr/share/applications/start-tor-browser.desktop

3.) Edit the Exec= line on my slightly modified start-tor-browser.desktop file (should now be in /usr/share/applications) to carry the full path of
    start-tor-browser executable inside the line starting with 'Exec='. After editing issue the following to make the newly edited file executable: 
    
        sudo chmod +x /usr/share/applications/start-tor-browser.desktop
    
4.) Tap the Tor Browser Icon on your Phosh interface and enjoy your Human Right to privacy/anonymity.

For Arch and most other distros, following the above video will leave you with a working Tor Browser Icon/button on your phone's desktop.

For Mobian, using the start-tor-browser.desktop file I modified slightly is needed for the Tor button to work on Mobian- if you use the original from sourceforge it will **NOT** start on Phosh Tor Browser button (until you use this file).

------------------------------------

Please Share to help me gain more views. :)

My Links:
Support/Blog: https://www.buymeacoffee.com/politictech
CashApp: $HumanRightsTech

I appreciate it. :)

------------------------------------

Official Tor Project website: www.torproject.org (I have no relation to the Tor Project, just trying to help fellow Linux Phone users and appreciate Tor)
Tor Pinephone Compatible Fork (Arm64): 
https://sourceforge.net/projects/tor-browser-ports/files/
