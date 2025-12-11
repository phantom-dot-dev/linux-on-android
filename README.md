# Overviews

This repo is about setting and using termux to run linux on anroid os.
Some working scrips are there in the scripts directory.

## Installing yt-dlp

```sh
termux-setup-storage                 # Allow termux to download files into your phone's storage
pkg update && pkg upgrade            # Update all packages
pkg install python python-pip        # Install Python and pip
pip install -U "yt-dlp[default]"     # Install yt-dlp with default dependencies
pkg install ffmpeg                   # OPTIONAL: Install ffmpeg
```

### Keyboard shortcut:
`ctrl + alt + left/right` -> to change desktop
`alt + ctrl` (customized) -> to change/cycle through running app. Note: `alt+esc` will not work, as pressing esc multiple times will not cycle, rather cancle the cycling window.

customizing: run `xfce4-settings-manager` command and change `window manager` -> shortcut settings

`alt + esc` (customized) for `application finder`
`alt + backticks` for triggering code suggession in `code oss`

### Performance:
Always keep the launching termux terminal open (behing the desktop). And must not minimized


While on xfce de, if mouse wheel is acting weird, like zooming, press `alt` once to fix.
Also, `alt + mouse-wheel` is used to zoom in/out the x11 de interface. 

* If `cmd + d` is pressed, all running apps in current desktop in android will be minimized, it will degrade the performance of the termux desktop. To fix keep open both termux terminal and x11 app. No need to restart everything.




