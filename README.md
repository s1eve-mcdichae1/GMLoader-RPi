## GMLoader-RPi

GMLoader - play GameMaker Studio games for Android on non-Android operating systems.

Installation scriptmodule for use with RetroPie (https://retropie.org.uk)

Tested RPi4 only. Please report success or failure on other platforms.

#### Droidports by JohnnyonFlame
https://github.com/JohnnyonFlame/droidports

[Temp: use s1eve-mcdichae1's fork with config dir patch https://github.com/s1eve-mcdichae1/droidports/commit/cc31738]

## Installation
Download the scriptmodule with command:

    wget https://raw.githubusercontent.com/s1eve-mcdichae1/GMLoader-RPi/main/gmloader.sh -P $HOME/RetroPie-Setup/scriptmodules/ports/

After that you can install the port through **RetroPie-Setup > Manage packages > Manage experimental packages**

#### Configuration:
ROM Extensions: .apk .APK

To configure the emulator launch commands for EmulationStation, you must first copy at least one APK file to `~/RetroPie/roms/ports/droidports/` and then run (or re-run) the installer.

#### Sample Content:
Maldita Castilla (official Ouya port) - a free traditional arcade game in the style of Ghosts'n Goblins: https://locomalito.com/juegos/Maldita_Castilla_ouya.apk
