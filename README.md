# Windhawk Dots
### My personal Windows config (meant for use with Windhawk).
![Example Screenshot](https://raw.githubusercontent.com/twigform/windhawk-dots/refs/heads/main/assets/example1.png)

> [!WARNING]  
> These configs are not perfectly stable or maintained by me! I'm willing to *try* to help with any issues, but there are NO guarantees.

## Prerequisites:
You will, of course, need [Windhawk](https://windhawk.net/) to use these. The configs here use the following mods:
- Taskbar Clock Customization
- Windows 11 Start Menu Styler
- Windows 11 Taskbar Styler
- Windows 11 Notification Center Styler
- Windows 11 Lock Screen Styler (some extra work is required to get this working, [here's a tutorial](https://github.com/AromaKitsune/Windows-XAML-Styles/blob/main/guides/Lock-Screen-Styling-Guide.md))

Some fonts are needed if you'd like idendical results, specifically: 

Google Sans Rounded (Private, closed source font. I'd reccomend simply changing the font name in the configs to something else. If you REALLY want it, you can rip the font "Google Sans Flex" from a rooted device running Android 16, and render out a custom font using it with the "rounded" paramters set to max.) 
[SF Pro Fonts](https://github.com/sahibjotsaggu/San-Francisco-Pro-Fonts/tree/master)

If you want text on your taskbar apps, there's a setting in Windows called "Combine taskbar buttons and hide labels". Simply set that to "When taskbar is full".

These configs are built for my laptop, which has a 1920x1200 display scaled at 125%. **All the configs SHOULD work** (I've tested on other devices), but keep this info in mind if using these on a normal 16:9 display scaled at 100%.

## Configs

### Taskbar / Popups

![Taskbar Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/taskbar.png?raw=true)
![Volume Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/volumeex.png?raw=true)

**Features/Modified Things:**
- Custom search text
- Custom subprocess icon
- Custom rounding/bar for popups
- Custom font
- Smiley in the clock :)

**Mods Required:**
- Windows 11 Taskbar Styler
- Taskbar Clock Customization

**Configs:**
- [Windows 11 Taskbar Styler](https://github.com/twigform/windhawk-dots/blob/main/configs/taskbar.json)
- [Taskbar Clock Customization](https://github.com/twigform/windhawk-dots/blob/main/configs/clock.json)

---------
### Notification Center / Control Center
![Notif Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/control.png?raw=true)

**Features/Modified Things:**
- Custom font
- Custom sliders for brightness/volume

**Mods Required:**
- Windows 11 Notification Center Styler

**Configs:**
- [Windows 11 Notification Center Styler](https://github.com/twigform/windhawk-dots/blob/main/configs/notificationcenter.json)

---------
### Start Menu / Search
![Search / Start Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/search.png?raw=true)
![Search / Start Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/start.png?raw=true)

**Features/Modified Things:**
- Hidden copilot button/other general bloat
- Custom font

**Mods Required:**
- Windows 11 Start Menu Center Styler

**Configs:**
- [Windows 11 Start Menu Center Styler](https://github.com/twigform/windhawk-dots/blob/main/configs/start.json)

---------
### Lock Screen
![Lock Screenshot](https://github.com/twigform/windhawk-dots/blob/main/assets/lock.png?raw=true)

**Features/Modified Things:**
- Custom font
- Custom spacing
- Rounded media controls


**Mods Required:**
- [Forked](https://github.com/AromaKitsune/Windows-XAML-Styles/blob/main/guides/Lock-Screen-Styling-Guide.md) Windows 11 Start Menu Center Styler


**Configs:**
- [Windows 11 Lock Screen Styler](https://github.com/twigform/windhawk-dots/blob/main/configs/lock.json)

