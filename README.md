# blue-pill-stm32
A simple(or not) guide to start programming blue-pill-stm32 microcontroller with PlatformIO in VSCode

# Disclaimer
This guide's main purpose is based on what works on my setup. I'm not responsible for any damage caused by this guide.

# Getting Started
This is my setup:
OS: Ubuntu 16.04 LTS
Board: stm32f103c8t6 (blue pill)
Uploader/Debugger: ST-LINK V2

Short version of the guide
1. Make sure you have a good internet connection.
2. Install VSCode.
3. Install C/C++ Extension.
4. Install PlatformIO.
  - Configure the serial port
5. Wire the board to ST-Link uploader.
6. Load an example arduino program to your blue pill stm32 board.

# Installation
VSCode can be installed using snap
```bash
  #install snap if you haven't
  sudo apt-get install snapd
  #installing vscode
  sudo snap install code --classic
```
to uninstall using snap
```bash
  sudo snap remove code
```

VSCode can also be installed using .deb package, simply install GDebi package installer, download VSCode .deb package, and open it using GDebi to install or uninstall VSCode.

You should be able to run VSCode now.

Next install C/C++ Extension and PlatformIO via extension manager.

