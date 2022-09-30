# Elementum

Elementum by [0xC0DE](https://twitter.com/0xC0DE6502), an 8-bit game for Acorn Electron, BBC Micro and BBC Master. Can also be played on a PC (Windows or Linux+Wine) with the self-contained EXE.

Download and play for free. Please donate to support me: [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S33YYQ7)

![Elementum Intro Screen](https://github.com/0xC0DE6502/elementum-releases/blob/main/res/introscreen.png?raw=true)

![Elementum Screenshot 1](https://github.com/0xC0DE6502/elementum-releases/blob/main/res/screenshot1.png?raw=true)
![Elementum Screenshot 2](https://github.com/0xC0DE6502/elementum-releases/blob/main/res/screenshot2.png?raw=true)
![Elementum Screenshot 3](https://github.com/0xC0DE6502/elementum-releases/blob/main/res/screenshot3.png?raw=true)
![Elementum Screenshot 4](https://github.com/0xC0DE6502/elementum-releases/blob/main/res/screenshot4.png?raw=true)

## Aim of the game
In a strange, hostile world electronic components have taken the 6502 CPU hostage. Its 8 status flags are scattered all over each of the 32 levels. You, a brave electron, have to collect the flags and free the 6502. Watch out for enemies, especially your nemesis: the positron. 

## How to play
There are 3 main ways to play the game:
1. Use the [tape image](https://github.com/0xC0DE6502/elementum-releases/raw/main/elementum.uef) on real hardware or an emulator
2. Use the [disk image](https://github.com/0xC0DE6502/elementum-eleases/raw/main/elementum.ssd) on real hardware or an emulator
3. Play the [self-contained EXE](https://github.com/0xC0DE6502/elementum-releases/raw/main/elementum.exe) on a PC

### Linux+Wine
The self-contained Windows EXE works on Linux as well if you use Wine: `wine elementum.exe`. You need a 64-bit `WINEPREFIX` and enough video memory configured (`winetricks videomemorysize=1024`). I have played the game successfully on Ubuntu 22.04 using Wine 7.18. Known issue: toggling full-screen play (`ALT+ENTER`) may cause the game to lose keyboard focus. Fix: use `ALT+TAB` to select the game window again.

## Controls (redefinable)

```
Z      - Left
X      - Right
RETURN - Jump
SHIFT  - Turbo
```

### Other keys

```
M     - Mode (normal, hard)
P     - Pause / Unpause
Q     - Quiet
S     - Sound
R     - Redefine controls
```

---

Elementum - Copyright (C) 2020-2021 [0xC0DE](https://twitter.com/0xC0DE6502)
