# Useful Snippets
## About
A collection of useful code snippets, commands, etc.

## Games
### Game Paths for Cloud Syncing
#### Basic Command
mklink /j "target identifier, i.e. the folder/file name that should go there" "the path to the existing folder/file"
#### Commands
(for future reference, these are based off my own setup and some folders may be things I added myself)  
```
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 4" "E:\Lightling\Save Games\Origin Games\TS 4"
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 3" "E:\Lightling\Save Games\Origin Games\TS 3"
```

### TS4
bb.ignoregameplayunlocksentitlement
cas.fulleditmode
testingcheats enabled

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