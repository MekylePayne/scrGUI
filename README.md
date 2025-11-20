 # scrGUI                                                                                                            
Stupidly Simple GUI for Scrcpy

![scrGUI UI](scrGUI-UI.png)

**scrGUI** is a lightweight, launcher for [scrcpy](https://github.com/Genymobile/scrcpy), designed for creators, testers, and tinkerers who want instant Android mirroring without the command line.

(Linux deployment in progress)

- Click-to-launch scrcpy with custom settings
- Save profiles for different devices or workflows
- No Python or ADB install required — just run `scrGUI.exe`
- Record Option, with native FPS

*!!NOTE: For some reason Windows Defender has detected my program as malicious, i have no idea for this reason as im not that good in programming, however if you know what the issue is please let me know so i can fix it, thank you. (used pyinstaller to compile the .py to .exe)!!*

## Key Features
Profiles
- Low: 640p / 2 Mbps
- Medium: 1080p / 4 Mbps
- High: 1920p / 8 Mbps
- Performance: 1920p / 16 Mbps - screen off, max throughput
(best for laptop screen-based gaming)
- Advanced: Custom resolution, bitrate, crop (saved persistently)

Toggles
- Fullscreen: Immersive monitor fill
- Always-on-top: Keeps window above others
- Show touches: Displays tap indicators

Options
- Keyboard: OTG passthrough typing
- No Display: Input only, no video
- Turn Screen Off: Saves battery & GPU
- Record: Timestamped video, optional folder

Advanced
- Custom res/bitrate: Fine-tune quality
- Record folder: Choose save location
- Crop: Focus on region (--crop w:h:x:y)
Example: --crop 720:1280:0:0
→ Captures a 720×1280 region from top-left corner

Combos
- Performance + Record: High-quality gameplay capture
- No Display + Keyboard: Passthrough typing
- Fullscreen + Always-on-top: Best for calls or reference
- Crop + Record: Focused app capture
- Touches + Record: Tutorial/demo videos

## Tutorial
1. First, make sure that you have the scrGUI.exe on your system (can be any directory)
2. Go on the device you want to mirror, head into settings and go to your phones info. Look for the build number/settings and click it as much times as you can, then you will have developer options enabled.
3. Once done, go back and into developer options (you might need to look around in settings since some phones hide it), once your in developer options scroll down until you see a option called USB Debugging. Enable it and leave the device.
4. Head back to your computer and double click the .exe file you downloaded. will take around 5seconds but once opened, choose any quality profile you want (use medium settings as a test for now.)
5. Now get your USB cable and connect the device you want to mirror to your laptop, then allow data transfer if needed. (if you get a USB Debugging request already, accept it)
6. If everything is correct, click on launch scrcpy, your phone will get a connection request, press allow. if it doesnt mirror your screen, click on launch scrcpy again.
7. If all steps were followed correctly, well done, scrGUI will mirror your screen and you can enjoy whatever you were doing. i recommend to close scrGUI, reopen it and click feature info. (very good information)

## Other

The .exe file is a portable package, so no need to install the app. 
I create this since most GUI based apps didnt have the features i wanted, hence i had to use the command line (which was really annoying after a while)

If you have any feature requests, give me a message on Discord (user: mekylepain)
