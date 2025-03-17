# Pywal4Plasma

![Screenshot_20250317_065009](https://github.com/user-attachments/assets/8880373c-a10a-42f2-8ad9-06acd746b238)
![Screenshot_20250317_064645](https://github.com/user-attachments/assets/7dc328c4-4f35-4abb-9fdb-e23bfa9077b6)
![Screenshot_20250317_064314](https://github.com/user-attachments/assets/2a755821-1655-476f-b6ef-507cbe3ba244)

# Dependencies
pywal16 3.8+ (AUR, GitHub)
Kvantum Theme Manager

# Instructions

1. Move the templates folder to ~/.config/wal/templates and rename it "Plasma"
2. Set your wallpaper using KDE Plasma's settings, not pywal
3. Run pywal: 'wal --cols16 -n -i /path/to/wallpaper'
4. Create the following symlinks

~/.cache/wal/Plasma/Kvantum -> ~/.config/Kvantum/Pywal

~/.cache/wal/Plasma/color-scheme.colors -> ~/.local/share/color-schemes/Pywal.colors

~/.cache/wal/Plasma/konsole.colorscheme -> ~/.local/share/konsole/Pywal.colorscheme

5. Go to System Settings -> Colors & Themes
6. Set Colors to Pywal
7. Set Application Style to Kvantum if not already
8. Open Kvantum Theme Manager & set theme to Pywal
9. Open Konsole and go to Edit Profile -> Appearance
10. Select Pywal and save

You will need to run the wal command above every time you change your wallpaper, but none of the other steps need to be redone.

Given that the Kvantum theme is made using Utterly Sweet as a base, I find that it looks best paired with the following:

Plasma Style: Utterly-Round (follows color scheme)

Window Decorations: Utterly-Round-Dark (also follows color scheme)

Feel free to experiment though!
