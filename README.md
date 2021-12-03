# Spotify-Hotkeys
Global hotkeys with play, pause, next track, previous track and app specific volume control.
## Installation/Usaage
Download the release, extract it and just run Spotify-Hotkeys.exe. The app will then launch spotify automatically and it will exit itself if spotify is closed, you can make a shortcut to the exe and place it on the desktop or taskbar.
## Default Hotkeys
Alt + Numpad 1️⃣: Prev track\
Alt + Numpad 2️⃣ Pause/Play\
Alt + Numpad 3️⃣: Next track\
Alt + Numpad ➖: Increase Volume\
Alt + Numpad ➕: Decrease volume
## Description
This is a project which uses nircmd and autohotkey to add hotkeys to spotify, if you prefer not running the exe then just swap out the exe with the ahk file in src. The reason for using nircmd is to control spotify's app volume individually, this is a really hacky way to do it and as such there is an issue with it. 
# Issue
Holding the volume increase button will cause a drastic cpu usage spike which lasts a few seconds. You are free to delete nircmd.exe, it would get rid of the issue and disable volume control.
