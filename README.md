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
