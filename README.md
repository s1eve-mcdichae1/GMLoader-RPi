## GMLoader-RPi

GMLoader - play GameMaker Studio games for Android on non-Android operating systems.

Installation scriptmodule for use with RetroPie:\
https://retropie.org.uk

Currently RPi4 only.

Droidports project by JohnnyonFlame:\
https://github.com/JohnnyonFlame/droidports

[Temp: use s1eve-mcdichae1's config dir patch (.config/apkname --> .config/gmloader/apkname):\
https://github.com/s1eve-mcdichae1/droidports/commit/cc31738]

## Installation
Download the scriptmodule to your Pi with command:

    wget https://raw.githubusercontent.com/s1eve-mcdichae1/GMLoader-RPi/main/gmloader.sh -P $HOME/RetroPie-Setup/scriptmodules/ports/

After that you can install the port through **RetroPie-Setup > Manage packages > Manage experimental packages**

ROM Extensions: .apk .APK

To configure the emulator run-command for EmulationStation, you must first copy at least one APK file to ~/RetroPie/roms/ports/droidports and then run (or re-run) the installer.
