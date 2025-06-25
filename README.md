# Matrix GRUB Theme (Customized by Kartik Halkunde)

# A customized version of the Fallout GRUB theme by shvchk, tweaked to better fit my personal style and setup as featured on r/unixporn.
✨ Changes Made

    Custom background image
    Font tweaks
    Icon tweaks
    Minor adjustments in theme.txt

## 📸 Preview

here

## 📦 Installation
```
git clone https://github.com/KartikHalkunde/Matrix-GRUB-theme.git
sudo cp -r Matrix-GRUB-theme /boot/grub/themes/Matrix
```
### Edit /etc/default/grub:

### GRUB_THEME="/boot/grub/themes/Matrix/theme.txt"

## Update grub:
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
## 🙏 Credits

``` Based on shvchk's Fallout GRUB Theme ```

## ✅ 4. Upload to GitHub
```
cd ~/Matrix-GRUB-theme
git init
git add .
git commit -m "Customized Matrix GRUB theme"
git remote add origin https://github.com/YOUR_USERNAME/Matrix-GRUB-theme.git
git push -u origin main
```
