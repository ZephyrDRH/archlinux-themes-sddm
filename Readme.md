Archlinux Theme for SDDM
------------------------
SDDM is a Login Manager for Linux which can be themed by qml. This is a port of existing kdm themes (package archlinux-themes-kdm) to SDDM. In addition, a KDE-branded theme has been added.

The Theme is available through AUR: 
* archlinux-themes-sddm
* https://aur.archlinux.org/packages/archlinux-themes-sddm/

![archlinux-simplyblack](archlinux-simplyblack/screenshot.png "archlinux-simplyblack")

![archlinux-soft-grey](archlinux-soft-grey/screenshot.png "archlinux-soft-grey")

 ![archlinux-kde](archlinux-kde/screenshot.png "archlinux-kde")


Manual Installation
-------------------

* copy the folder(s) to /usr/share/sddm/themes/

  ```
  $ sudo cp -r archlinux-simplyblack/  /usr/share/sddm/themes/
  $ sudo cp -r archlinux-soft-grey/  /usr/share/sddm/themes/  
  $ sudo cp -r archlinux-kde/  /usr/share/sddm/themes/

  ```
* change the current theme in System Settings or in sddm.conf (here for archlinux-kde): 

  ```
  $ sudo vim /etc/sddm.conf
  
  [Theme]
  Current=archlinux-kde 
  ```
* Have fun!
