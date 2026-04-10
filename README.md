# 🐧 My Arch GRUB Theme
A sleek, high-performance GRUB theme for Arch Linux, inspired by Mecha Sonic and the Vimix grub theme.


## 🚀 Features
* 🖼️ High-res background
* 🐧 Clean Arch Linux logo
* 🐧 based on vimix modern grub theme
* 🎨 Customization: Easily toggle the logo version (see Notes).
 
## 🛠️ Installation
1. Copy folder to `/usr/share/grub/themes/` or wherever are themes in your machine.
2. Edit `/etc/default/grub` and update the theme path:
   ```bash
   GRUB_THEME="/usr/share/grub/themes/Mecha_Sonic_Scrapnik_grub_theme/theme.txt"
3. Run `grub-mkconfig`

### note1: To remove the logo, swap "background.jpg" name with "_background.jpg".
### note2: Based on the Vimix Modern GRUB theme. Please provide attribution if redistributed.
