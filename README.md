# mess-standalone
MESS, the Multi Emulator Super System, is a part of the MAME project that aims to emulate various gaming consoles and computers. MESS supports a fairly large number of standalone/dedicated vintage gaming machines which will play quite well on a television or computer monitor if set up correctly.

The files in this repo are a selection intended to be used with an enhanced version of the RetroPie-Setup script (offered here: https://github.com/valerino/RetroPie-Setup/) in order to make configuring and playing those games very simple. The idea is that the configuration should be reduced to just putting the correct files in the correct directories, with zero code, scripting, or commands needed.

1. Follow the basic instructions there to install the replacement RetroPie-Setup script.
2. Via the RetroPie --> RetroPie Setup --> Manage packages --> Manage experimental packages menu, install the lr-mess emulator and then the lr-mess-standalone quasi-emulator.
3. Place the .spec files from this repo in your ~/RetroPie/roms/standalone directory. You can alter the names to reflect what you want to see in the EmulationStation games list.
4. Add the bioses for the systems that interest you to your system ~/RetroPie/BIOS dir.
5. (Optional) Add artwork for the systems that interest you to ~/RetroPie/roms/standalone/artwork using the names that match the system names defined by MESS in the Name column of the master systems table: http://www.progettoemma.net/mess/sysset.php
6. Restart EmulationStation and launch your standalone systems!
7. (Optional) Add addition spec files on your own in order to experience more MESS-supported systems. The files literally only contain the few characters that identify the system and nothing more, so just create them, do the bios and artwork steps above, and restart EmulationStation.

As an example, let's say you wanted to experience the classic Milton Bradley game, Simon. You know it, it is the one with 4 large colored buttons that beep a sequence which need to be replayed by the player. After the basic emulator install, you would place the file "Simon (Milton Bradley).spec" in your ~/RetroPie/roms/standalone directory, the simon.zip bios file available on the internet in your ~/RetroPie/BIOS directory, and a different simon.zip artwork file available on the internet in your ~/RetroPie/roms/standalone/artwork directory. Once EmulationStation is restarted you will be playing Simon through your RetroPie setup!
