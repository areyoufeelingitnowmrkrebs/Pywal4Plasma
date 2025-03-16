# Pywal4Plasma
Pywal16 templates for KDE Plasma's color scheme, Kvantum, and Konsole using Utterly Sweet as a base

DEPENDS: pywal16 3.8+ (AUR, GitHub), Kvantum Theme Manager

HOW TO USE:

1. Move the templates folder to ~/.config/wal/templates and rename it "Plasma"
2. Set your wallpaper using KDE Plasma's settings, not pywal
3. Run pywal: 'wal --cols16 -n -i /path/to/wallpaper'
4. Create the following symlinks

~/.cache/wal/Kvantum -> ~/.config/Kvantum/Pywal

~/.cache/wal/color-scheme.colors -> ~/.local/share/color-schemes/Pywal.colors

~/.cache/wal/konsole.colorscheme -> ~/.local/share/konsole/Pywal.colorscheme

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
