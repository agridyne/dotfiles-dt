# dotfiles-dt
As requested, I will be working on creating a full in-depth guide on how I achieved my setup. For now, all I have is just a basic overview of what I did along with a .zip file. This will be my first tutorial for anything like this so please bear with me. I don't have dotfiles quite yet, but I'll work on getting them here. My setup is still a work in progress and not everything has been riced. I will continue to add to this repo as things change/get updated.
# Rice Configuration
## DISTRO:
CachyOS
## DESKTOP ENVIRONMENT:
KDE Plasma
### KDE Plugins/Settings:
- Global Theme - Installed Monochrome KDE by *pwyde* (used as starting point)
- Colors - Used the one from Monochrome KDE
- Application Style: Used default Breeze
- Plasma Style: Used default Breeze
- Window Decorations: Used default Breeze
- Icons: Installed Yet Another Monochrome Icon Set For KDE Plasma by *dirn*
- Cursors: Bibata-Modern-Ice
- Splash Screen: Installed Kuro the cat by *a2-n*
- Login Screen (SDDM): Installed Monochrome Plasma 6 by *pwyde*
- Boot Splash Screen: Installed dotLock by *vrag*
- Video Wallpaper for Desktop and Lockscreen: Installed Smart Video Wallpaper by *adhec*
### KDE WIDGETS:
- CatWalkR (Cat in panel; top right)
- KDE control station (Menu for panel; top right)
- Kurve (Audio visualizer; left side of screen)
	- Refer to screenshots for config
- YoRHa HUD (System monitoring mainly for looks; right side of screen)
- Thermal Monitor (More system monitoring for looks; below YoRHa HUD)
- Panel Colorizer (Used to create panel "islands")
	- Using two panels; 1 for top and 1 for bottom
	- Place the "Main Blur" and "Main Setup" folders in ~/.config/panel-colorizer/presets/
	- Then change your settings to match my screenshots
- System Monitor (Default KDE widgets in panel; top left)
- Digital Clock (Default KDE widget on desktop; bottom left)
## FONT:
JetBrainsMono Nerd Font (Used system wide)
## SHELL:
fish (but I plan to move to zsh)
## TERMINAL:
cool-retro-term
- I attached my .json for cool retro term (You can import it using the context menu when launching the terminal).
## BROWSER:
zen
- To achieve the transparent background I followed this guide https://sameerasw.com/zen and since I'm on KDE, I had to also use *kwin-effects-better-blur-dx* for this to work
	- Refer to screenshots for kwin-effects-better-blur-dx configs
- Firefox extensions used
	- Bonjourr (new tab/home page with greeting, quote, search bar)
	- Dark Reader (to auto set websites to dark mode; used in conjunction with Zen Internet extension)
	- Zen Internet (achieve transparency and blur; used in conjunction with Dark Reader extension; and dependent on Transparent Zen mod)
- Zen mods used
	- Animations Plus
	- Audio Indicator Enhanced
	- Better Find Bar
	- Floating History
	- Floating Status Bar
	- Load Bar
	- Transparent Zen (Requirement for Zen Internet)
## WALLPAPERS:
- https://www.desktophut.com/synthwave-dreamwave-girl
- https://www.desktophut.com/digital-gaze-8642
## WIP:
- vivaldi (haven't riced yet)
- vencord (not showcased; currently working on)
- vim (haven't riced yet)
- converting all application icons in use to monochrome
- SDDM login screen (I changed to SDDM from Plasma login; still working on this as I plan to have this be a video as well)
- Lock screen (I changed the background to be a video but I'm working on the layout and I also plan to remove the watermark on the video at some point).
- Custom fastfetch
