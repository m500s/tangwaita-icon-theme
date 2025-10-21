# **Tangwaita**

<img width="1535" height="1175" alt="tangwaita" src="https://github.com/user-attachments/assets/aec1ba64-844c-488e-80ea-68fb45de9108" /> <br />

Inspired by the Tango icon theme, this is a direct replacement for the Adwaita fullcolor icons.    
The icons were either modified or taken directly from the Tango icon set or designed in the Tango style.  
Extra icons for some of the standard gnome applications and some browsers are also included.  
All the icons are public domain.

Thanks to the original Tango designers. Thanks to openclipart for the base svgs for the usb and phone icons. 

---

### Requires (these are inherited by the Tangwaita theme)  

1) For the standard symbolic icon set
* adwaita-icon-theme   
2) For complete coverage of legacy fullcolor icons  
  * tango-icon-theme (recommended, along with one of one of the below)
  * adwaita-icon-theme-legacy   
  * gnome-icon-theme  

---

Delete the extras folder if you only want the standard Adwaita fullcolor icons.

For browsers other than chromium or firefox, rename internet-web-browser.svg using the icon name from the browser's desktop file (e.g. google-chrome.svg)  

---

### Install

single user
1) copy the tar.xz into ~/.local/share/icons and run 'tar -xf tangwaita-icon-theme-1.0.tar.xz'  
2) run 'gtk-update-icon-cache -f ~/.local/share/icons/tangwaita-icon-theme' to update the icon cache

systemwide 
1) use dnf to install the rpm or repeat the single user instructions using /usr/share/icons instead
 
---

[Adwaita Icon Theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme) - the standard icon set for the GNOME core apps

[Tango Icon Theme Guidelines](https://web.archive.org/web/20060519123558/http://tango-project.org/Tango_Icon_Theme_Guidelines)  - archived at web.archive.org
