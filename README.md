# Cinnamon Patch
Fixes the confusing highlighting in the Grouped Window List panel

| BEFORE | AFTER |
| ----------- | ----------- |
| ![](https://i.imgur.com/SUlliUU.png) | ![](https://i.imgur.com/bPbptE3.png) | 

# Arc Theme
Arc is a flat theme with transparent elements for GTK 3, GTK 2 and various desktop shells, window managers and applications. It's well suited for GTK based desktop environments such as GNOME, Cinnamon, Xfce, Unity, MATE, Budgie etc.

The theme was originally designed and developed by [horst3180](https://github.com/horst3180/arc-theme), but the project has been unmaintained since May 2017.

This fork aims to keep the theme updated with new toolkit and desktop environment versions, resolve pre-existing issues, and improve and polish the theme while preserving the original visual design.

This theme uses node-sass/libsass to process the various .scss files. Never edit any of the .css files manually.

## Arc is available in four variants 

##### Arc

![A screenshot of the Arc theme](http://i.imgur.com/Ph5ObOa.png)

##### Arc-Darker

![A screenshot of the Arc-Darker theme](http://i.imgur.com/NC6dqyl.png)

##### Arc-Dark

![A screenshot of the Arc-Dark theme](http://i.imgur.com/5AGlCnA.png)

##### Arc-Lighter

![A screenshot of the Arc-Lighter theme](https://raw.githubusercontent.com/jnsh/arc-theme/master/.github/arc-lighter-prv.png)

## Supported toolkits and desktops

Arc comes with themes for the following

- GTK 2
- GTK 3
- GTK 4
- GNOME Shell >= 3.28
- Cinnamon >= 3.8
- Unity
- Metacity
- Xfwm
- Plank

## Manual Installation
```
mkdir ~/.themes
git clone https://github.com/clerizedd/arc-theme.git
cd arc-theme
cp -r Arc Arc-Dark Arc-Darker Arc-Lighter ~/.themes
```