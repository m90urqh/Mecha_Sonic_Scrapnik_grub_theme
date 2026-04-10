# 🐧 My Arch GRUB Theme
A sleek, high-performance GRUB theme for Arch Linux, inspired by Mecha Sonic and the Vimix grub theme.
A live look at the Mecha Sonic Scrapnik theme running on Arch Linux.
![mechasonic_grub_theme_showcase](https://github.com/user-attachments/assets/ab27aa8b-51d5-4ea7-ac1c-fdf453ad4a80)


## 🚀 Features
* 🖼️ High-res background
* 🐧 Clean Arch Linux logo
* 🐧 based on vimix modern grub theme
* 🎨 Customization: Easily toggle the logo version (see Notes).
 
## 🛠️ Installation
1. Copy folder to `/usr/share/grub/themes/` or wherever are themes in your machine.
2. Edit `/etc/default/grub` and update the theme path:
   ```bash
   GRUB_THEME="/usr/share/grub/themes/Mecha_Sonic_Scrapnik_grub_theme-main/theme.txt"
3. Run `grub-mkconfig`

### note1: To remove the logo, swap "background.jpg" name with "_background.jpg".
### note2: Based on the Vimix Modern GRUB theme. Please provide attribution if redistributed.
> [!TIP]
> **Screen Resolution & Scaling:** If the menu rectangle doesn't align correctly with your screen, I have included two "clean" versions of the background without the baked-in UI.
> 
> * **To Fix:** Replace `background.jpg` with one of the alternative images in the folder.
> * **Bonus:** These images work great as standalone desktop wallpapers too!
