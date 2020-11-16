# Useful Snippets
## About
A collection of useful code snippets, commands, etc.

## Games
### Game Paths for Cloud Syncing
Because Windows has like 80 folders that games can save to, backups may be difficult. Use symbolic links (use /j for certain games like Minecraft which may not work with default symbolic link)
#### Basic Command
`mklink /j "target identifier, i.e. the folder/file name that should go there" "the path to the existing folder/file"`
#### Commands
(for future reference; these are based off my own setup and some folders may be things I added myself; put as many here as possible for one massive copy-paste anytime I want to reinstall Windows or do something that breaks this stuff)  
```
mklink /j "E:\Lightling\Libraries\Documents\Square Enix\Just Cause 3" "E:\Lightling\Save Games\Steam Games\Just Cause 3"
mklink /j "C:\Users\Lightling\AppData\Roaming\.minecraft" "D:\Games\Mojang\.minecraft"
mklink /j "D:\Games\Mojang\.minecraft\saves" "E:\Lightling\Save Games\Other Games\Minecraft\saves"
mklink /j "C:\Users\Lightling\AppData\Local\AvenColony" "E:\Lightling\Save Games\GOG Games\Aven Colony"
mklink /j "E:\ProgramData\GOG Games\Dungeon Keeper Gold\SAVE" "E:\Lightling\Save Games\GOG Games\Dungeon Keeper\SAVE"
mklink /j "E:\ProgramData\GOG Games\Dungeon Keeper 2\Data\Save" "E:\Lightling\Save Games\GOG Games\Dungeon Keeper 2\Save"
mklink /j "E:\ProgramData\GOG Games\Fallout\DATA\SAVEGAME" "E:\Lightling\Save Games\GOG Games\FO 1\SAVEGAME"
mklink /j "E:\ProgramData\GOG Games\Fallout 2\data\savegame" "E:\Lightling\Save Games\GOG Games\FO 2\savegame"
mklink /j "E:\ProgramData\GOG Games\Fallout Tactics\core\user" "E:\Lightling\Save Games\GOG Games\FO T\user"
mklink /j "C:\Users\Lightling\AppData\LocalLow\CampoSanto\Firewatch\saves" "E:\Lightling\Save Games\GOG Games\Firewatch\saves"
mklink /j "E:\Lightling\Libraries\Documents\My Games\FasterThanLight" "E:\Lightling\Save Games\GOG Games\FTL"
mklink /j "C:\Users\Lightling\AppData\LocalLow\Team Cherry\Hollow Knight" "E:\Lightling\Save Games\GOG Games\Hollow Knight"
mklink /j "C:\Users\Lightling\AppData\Local\sirengame\SaveGames" "E:\Lightling\Save Games\GOG Games\Rime\SaveGames"
mklink /j "E:\ProgramData\GOG Games\Star Wars - KotOR\saves" "E:\Lightling\Save Games\GOG Games\SW - KOTOR\saves"
mklink /j "E:\ProgramData\GOG Games\Star Wars - KotOR2\saves" "E:\Lightling\Save Games\GOG Games\SW - KOTOR2\saves"
mklink /j "C:\Users\Lightling\AppData\Roaming\Surviving Mars" "E:\Lightling\Save Games\GOG Games\Surviving Mars"
mklink /j "C:\Users\Lightling\AppData\Roaming\Nightdive Studios\System Shock EE" "E:\Lightling\Save Games\GOG Games\SS Enhanced"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_0" "E:\Lightling\Save Games\GOG Games\SS 2\save_0"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_1" "E:\Lightling\Save Games\GOG Games\SS 2\save_1"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_2" "E:\Lightling\Save Games\GOG Games\SS 2\save_2"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_3" "E:\Lightling\Save Games\GOG Games\SS 2\save_3"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_4" "E:\Lightling\Save Games\GOG Games\SS 2\save_4"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_5" "E:\Lightling\Save Games\GOG Games\SS 2\save_5"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_6" "E:\Lightling\Save Games\GOG Games\SS 2\save_6"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_7" "E:\Lightling\Save Games\GOG Games\SS 2\save_7"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_8" "E:\Lightling\Save Games\GOG Games\SS 2\save_8"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_9" "E:\Lightling\Save Games\GOG Games\SS 2\save_9"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_10" "E:\Lightling\Save Games\GOG Games\SS 2\save_10"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_11" "E:\Lightling\Save Games\GOG Games\SS 2\save_11"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_12" "E:\Lightling\Save Games\GOG Games\SS 2\save_12"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_13" "E:\Lightling\Save Games\GOG Games\SS 2\save_13"
mklink /j "E:\ProgramData\GOG Games\System Shock 2\save_14" "E:\Lightling\Save Games\GOG Games\SS 2\save_14"
mklink /j "E:\Lightling\Libraries\Documents\Paradox Interactive\Stellaris" "E:\Lightling\Save Games\GOG Games\Stellaris"
mklink /j "E:\Lightling\Libraries\Documents\The Witcher" "E:\Lightling\Save Games\GOG Games\Witcher"
mklink /j "E:\Lightling\Libraries\Documents\Witcher 2" "E:\Lightling\Save Games\GOG Games\Witcher 2"
mklink /j "E:\Lightling\Libraries\Documents\The Witcher 3" "E:\Lightling\Save Games\Steam Games\Witcher 3"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Anthem" "E:\Lightling\Save Games\Origin Games\Anthem"
mklink /j "C:\Users\Lightling\AppData\Local\Criterion Games\Burnout Paradise Remastered" "E:\Lightling\Save Games\Origin Games\Burnout Paradise Remastered"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect" "E:\Lightling\Save Games\Origin Games\Mass Effect"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect 2" "E:\Lightling\Save Games\Origin Games\Mass Effect 2"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect 3" "E:\Lightling\Save Games\Origin Games\Mass Effect 3"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect Andromeda" "E:\Lightling\Save Games\Origin Games\Mass Effect Andromeda"
mklink /j "E:\Lightling\Libraries\Documents\Respawn\Titanfall2" "E:\Lightling\Save Games\Origin Games\Titanfall2"
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 3" "E:\Lightling\Save Games\Origin Games\TS 3"
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 4" "E:\Lightling\Save Games\Origin Games\TS 4"
```

### TS4
```
testingcheats 1
cas.fulleditmode
bb.ignoregameplayunlocksentitlement
```

## CLI
### Windows
#### Empty Folder Removal
NOTE: THIS COMMAND WILL REMOVE SYMBOLIC LINKS, use in a directory you know doesn't have symbolic links
```
for /f "delims=" %i in ('dir /s /b /ad ^| sort /r') do rd "%i" 2>NUL
```
READONLY:  
```
for /r "C:\" /d %F in (.) do @dir /b "%F" | findstr "^" >nul || echo %~fF
```

#### Mass Rename
NOTE: This must be run in powershell, not command prompt  
NOTE: This is based off of running Caesium, which by default adds `_compressed`; this can be changed and even removed, but I keep it to determine compression delta; replace the directory with whatever necessary, and replace "_compressed" with what is getting replaced
```
get-childitem C:\Users\Lightling\Projects\Development\Web\Lightling\images -recurse -file | foreach {Rename-item $_.FullName -NewName ($_.FullName -replace "_compressed")}
PAUSE
```

## Utilities
### Odrive
#### Trash Removal (requires Python)
Sometimes, if the trash bin gets too large, the context-menu for the trash bin won't load. To sync deletes, do the following:
0. Ensure odrive is fully loaded (command will return an error if not running, command will have no effect if it hasn't detected trash yet/hasn't fully loaded)
1. open cmd prompt at C:\Users\Lightling\.odrive\bin\6769\cli
2. run `python odrive.py emptytrash`

### OS Flashing
#### Windows
Rufus  
GPT, UEFI, NTFS  
Doesn't ask for Mode  

#### Ubuntu (THIS CURRENTLY ISN'T WORKING)  
Rufus  
GPT, UEFI, FAT32  
ISO Mode  

#### Manjaro (THIS CURRENTLY ISN'T WORKING)
Rufus  
GPT, UEFI, FAT  
Doesn't ask for Mode  

#### OpenSUSE
Rufus  
GPT, UEFI, FAT32  
DD Image Mode  

if something gets converted to MBR (certain utilities love to do this without warning; e.g., Etcher):
```
diskpart
list disk
select disk #
clean
convert gpt
```
