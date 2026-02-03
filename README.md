# **Tangwaita**
### Fullcolor icons
<img width="1501" height="1169" alt="fullcolor" src="https://github.com/user-attachments/assets/5adf10e6-8ac4-40d8-bfd9-6833b88ae6f5" /><br />
### Core apps
<img width="1359" height="501" alt="coreapps" src="https://github.com/user-attachments/assets/1f4dd49e-2274-4d58-8963-8f07237409f0" /><br />
### Extras
<img width="747" height="338" alt="extras" src="https://github.com/user-attachments/assets/cb652fd9-fbbf-4c6b-a38e-4c03f1a67fd0" />

Inspired by the Tango icon theme, this is a direct replacement for the Adwaita fullcolor icons and GNOME core app icons.    
The icons were either modified or taken directly from the Tango icon set or designed in the Tango style.  
Extra icons for browsers and a few additional GNOME applications are also included.  
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

### Install

single user
1) extract the tar.gz into ~/.local/share/icons
2) run 'gtk-update-icon-cache -f ~/.local/share/icons/tangwaita-icon-theme' to update the icon cache

systemwide 
1) use dnf to install the rpm or repeat the single user instructions using /usr/share/icons instead

---

### Notes

1) For browsers other than chromium or firefox, rename internet-web-browser.svg using the icon name from the browser's desktop file (e.g. google-chrome.svg)  
2) Copy Override.xml to /usr/share/mime/packages and run 'update-mime-database /usr/share/mime/' to correctly assign icons to mimetypes (pdfs and certificates for now) 
3) Edit index.theme to use other full icon sets (e.g. Inherits=elementary-xfce,Adwaita,hicolor)

---

Thanks to the original Tango designers.  
Thanks to openclipart for some base svgs, particularly the usb, phone, eggplant, bookshelf and question mark. 

[Adwaita Icon Theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme) - the standard fullcolor icon set  
[GNOME Core Apps](https://apps.gnome.org) - the GNOME core apps  
[Tango Icon Theme Guidelines](https://web.archive.org/web/20060519123558/http://tango-project.org/Tango_Icon_Theme_Guidelines)  - archived at web.archive.org
