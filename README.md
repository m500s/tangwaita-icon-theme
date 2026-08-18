# **Tangwaita**
### Fullcolor icons
<img width="1366" height="1338" alt="fullcolor" src="https://github.com/user-attachments/assets/089a5d93-8632-4188-b8f8-f2d102f10bf0" /><br />
### Core apps
<img width="1069" height="670" alt="core apps" src="https://github.com/user-attachments/assets/364ccd88-f88a-49c1-950e-67e5be211c57" /><br />
### Extras
<img width="768" height="346" alt="extras" src="https://github.com/user-attachments/assets/88705fdb-b2da-48ee-8e8b-379550fe181a" /><br />

---

Inspired by the Tango icon theme, this is a direct replacement for the Adwaita fullcolor icons and GNOME core app icons. The icons were either modified or taken directly from the Tango icon set or designed in the Tango style. Extra icons for browsers and a few additional GNOME applications are also included.  
<br />
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
3) Edit index.theme to use other legacy fullcolor icon sets (e.g. Inherits=elementary-xfce,Adwaita,hicolor)

---

Thanks to the original Tango designers.  
Thanks to openclipart for some base svgs, particularly the usb, phone, eggplant, bookshelf and question mark. 

[Adwaita Icon Theme](https://gitlab.gnome.org/GNOME/adwaita-icon-theme) - the standard fullcolor icon set  
[GNOME Core Apps](https://apps.gnome.org) - the GNOME core apps  
[Tango Icon Theme Guidelines](https://web.archive.org/web/20060519123558/http://tango-project.org/Tango_Icon_Theme_Guidelines)  - archived at web.archive.org
