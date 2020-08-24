# Remote Desktop connection for Linux Mint 20 Cinnamon

1. Install Xrdp and Xorg with the software manager
  `sudo apt install xorg xorgrdp`

2. Install Freerdp2-x11
  `sudo apt install freerdp2-x11`
  
3. @Terminal (did both with root and normal user):
  `echo env -u SESSION_MANAGER -u DBUS_SESSION_BUS_ADDRESS cinnamon-session>~/.xsession`
  
4. Reboot
  `sudo reboot`

5. When logging in, use Xorg as the session managaer
  
  
TODO:
  1. Test performance on a decent network connection.
  
Source:
  https://forums.linuxmint.com/viewtopic.php?t=272329
