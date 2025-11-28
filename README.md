I updated the flatpak from the repo of sonic 2006 recompiled and sonic unleashed:
https://github.com/sonicnext-dev/MarathonRecomp
https://github.com/hedge-dev/UnleashedRecomp

But you still need the Game.iso file you can probibly find that in the [roms megathread](https://r-roms.github.io/Microsoft/microsoft-xbox360) if you dont own it

if flatpak wont run on wayland use:
```bash
flatpak run appid --sdl-video-driver wayland
```
