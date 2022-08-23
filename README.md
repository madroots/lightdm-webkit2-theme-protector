# Thanks for using PROTECTOR lightdm-webkit2 theme
# This theme is forked from "minimal" theme.
# 
# Original theme Github repo: 
# https://github.com/allacee/lightdm-webkit2-theme-minimal
# 
#
#


## Installation of the protector theme
1. Clone or download this repo
2. Copy the content of the repo to /usr/share/lightdm-webkit/themes/protector/
2. Install `lightdm` and `lightdm-webkit2-greeter` (if you cannot find it in repositories, download precompiled binary from project site and install)
4. Set webkit2 greeter as a greeter. Edit file (create if needed): `/etc/lightdm/lightdm.conf`: 

[Seat:*]

greeter-session=lightdm-webkit2-greeter

5. Set this theme as greeter theme. Edit file `/etc/lightdm/lightdm-webkit2-greeter.conf`:

webkit_theme = protector

6. Set your display manager to LightDM if you haven't already
7. Reboot and enjoy
