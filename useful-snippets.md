# Useful Snippets
## About
A collection of useful code snippets, commands, etc.

## Games
### Game Paths for Cloud Syncing
Because Windows has like 80 folders that games can save to, backups may be difficult. Use symbolic links (use /j for certain games like Minecraft which may not work with default symbolic link)
#### Basic Command
mklink /j "target identifier, i.e. the folder/file name that should go there" "the path to the existing folder/file"
#### Commands
(for future reference; these are based off my own setup and some folders may be things I added myself; put as many here as possible for one massive copy-paste anytime I want to reinstall Windows or do something that breaks this stuff)  
```
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 4" "E:\Lightling\Save Games\Origin Games\TS 4"
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 3" "E:\Lightling\Save Games\Origin Games\TS 3"
```

### TS4
```
bb.ignoregameplayunlocksentitlement
cas.fulleditmode
testingcheats enabled
```

## CLI
### Empty Folder Removal
NOTE: THIS COMMAND WILL REMOVE SYMBOLIC LINKS, use in a directory you know doesn't have symbolic links
```
for /f "delims=" %i in ('dir /s /b /ad ^| sort /r') do rd "%i" 2>NUL
```
READONLY:  
```
for /r "C:\" /d %F in (.) do @dir /b "%F" | findstr "^" >nul || echo %~fF
```

## Utilities
### Odrive
#### Trash Removal (requires Python)
Sometimes, if the trash bin gets too large, the context-menu for the trash bin won't load. To sync deletes, do the following:
0. Ensure odrive is fully loaded (command will return an error if not running, command will have no effect if it hasn't detected trash yet/hasn't fully loaded)
1. open cmd prompt at C:\Users\Lightling\.odrive\bin\6769\cli
2. run `python odrive.py emptytrash`

### OS Flashing
Windows:
Rufus
GPT, UEFI, NTFS
Doesn't ask for Mode

Ubuntu: THIS CURRENTLY ISN'T WORKING
Rufus
GPT, UEFI, FAT32
ISO Mode

Manjaro: THIS CURRENTLY ISN'T WORKING
Rufus
GPT, UEFI, FAT
Doesn't ask for Mode

OpenSUSE:
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