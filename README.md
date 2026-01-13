# **Tangwaita**
### Fullcolor icons
<img width="1500" height="1169" alt="fullcolor_icons" src="https://github.com/user-attachments/assets/d0c899df-7e65-476e-ba66-41aeac331ef9" /><br />
### Core apps
<img width="1359" height="500" alt="coreapps_icons" src="https://github.com/user-attachments/assets/5af85bc9-f14d-4abf-8f4d-52e9830b177e" /><br />

Inspired by the Tango icon theme, this is a direct replacement for the Adwaita fullcolor icons and GNOME core app icons.    
The icons were either modified or taken directly from the Tango icon set or designed in the Tango style.  
Extra icons for a few additional GNOME applications and browsers are also included.  
All the icons are public domain.

---

### Requires
* adwaita-icon-theme - for the standard symbolic icon set   
### Recommended   
* tango-icon-theme
* gnome-icon-theme - for complete coverage of legacy fullcolor icons  
<br />
All three themes are inherited in index.theme in the order: Tango, gnome, Adwaita

---

For browsers other than chromium or firefox, rename internet-web-browser.svg using the icon name from the browser's desktop file (e.g. google-chrome.svg)  

---

### Install

single user
1) extract the tar.gz into ~/.local/share/icons
2) run 'gtk-update-icon-cache -f ~/.local/share/icons/tangwaita-icon-theme' to update the icon cache

systemwide 
1) use dnf to install the rpm or repeat the single user instructions using /usr/share/icons instead
 
---

Thanks to the original Tango designers.  
Thanks to openclipart for some base svgs, particularly the usb, phone, eggplant, bookshelf and question mark. 

[Adwaita Icon Theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme) - the standard fullcolor icon set 
[GNOME Core Apps](https://apps.gnome.org) - the GNOME core apps

[Tango Icon Theme Guidelines](https://web.archive.org/web/20060519123558/http://tango-project.org/Tango_Icon_Theme_Guidelines)  - archived at web.archive.org
