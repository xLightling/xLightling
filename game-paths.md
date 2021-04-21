```
REM UTIL ensure these common directories exist; ensure the games themselves are installed as well, that won't be included here
mkdir "C:\Users\Lightling\AppData\Roaming"
mkdir "C:\Users\Lightling\AppData\Local"
mkdir "C:\Users\Lightling\AppData\LocalLow"
mkdir "E:\Lightling\Libraries\Documents\My Games"
mkdir "E:\Lightling\Libraries\Saved Games"



REM STEAM

mklink /j "C:\Users\Lightling\AppData\Local\Amid Evil" "E:\Lightling\Save Games\Steam Games\Amid Evil"

mkdir "E:\ProgramData\Steam Games\steamapps\common\Aporia\user"
mklink /j "E:\ProgramData\Steam Games\steamapps\common\Aporia\user\savegames" "E:\Lightling\Save Games\Steam Games\Aporia - BtV\savegames"

mkdir "C:\Users\Lightling\AppData\LocalLow\onemangames"
mklink /j "C:\Users\Lightling\AppData\LocalLow\onemangames\Artificial Defense" "E:\Lightling\Save Games\Steam Games\Artificial Defense"

mkdir "C:\Users\Lightling\AppData\Local\Colossal Order"
mklink /j "C:\Users\Lightling\AppData\Local\Colossal Order\Cities_Skylines" "E:\Lightling\Save Games\Steam Games\CitiesSkylines"

mkdir "C:\Program Files (x86)\Steam\userdata\114217869\205100"
mklink /j "C:\Program Files (x86)\Steam\userdata\114217869\205100\remote " "E:\Lightling\Save Games\Steam Games\Dishonored\remote"

mkdir "E:\Lightling\Libraries\Saved Games\Arkane Studios"
mklink /j "E:\Lightling\Libraries\Saved Games\Arkane Studios\Dishonored2" "E:\Lightling\Save Games\Steam Games\Dishonored2"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Distance" "E:\Lightling\Save Games\Steam Games\Distance"

mkdir "E:\Lightling\Libraries\Saved Games\id Software\DOOM"
mklink /j "E:\Lightling\Libraries\Saved Games\id Software\DOOM\base" "E:\Lightling\Save Games\Steam Games\Doom 2016\base"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Fallout3" "E:\Lightling\Save Games\Steam Games\FO 3"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Fallout4" "E:\Lightling\Save Games\Steam Games\FO 4"

mklink /j "E:\Lightling\Libraries\Documents\My Games\FalloutNV" "E:\Lightling\Save Games\Steam Games\FO NV"

mkdir "C:\Program Files (x86)\Steam\userdata\114217869\265930"
mklink /j "C:\Program Files (x86)\Steam\userdata\114217869\265930\remote" "E:\Lightling\Save Games\Steam Games\Goat Sim\remote"

mkdir "E:\Lightling\Libraries\Documents\Square Enix"
mklink /j "E:\Lightling\Libraries\Documents\Square Enix\Just Cause 3" "E:\Lightling\Save Games\Steam Games\Just Cause 3"

mkdir "C:\Program Files (x86)\Steam\userdata\114217869\356190"
mklink /j "C:\Program Files (x86)\Steam\userdata\114217869\356190\remote" "E:\Lightling\Save Games\Steam Games\Shadow of War"
mklink /j "C:\Users\Lightling\AppData\Local\WB Games\Shadow of War" "E:\Lightling\Save Games\Steam Games\Shadow of War"

mkdir "E:\ProgramData\Steam Games\steamapps\common\Nelo\Nelo"
mklink /j "E:\ProgramData\Steam Games\steamapps\common\Nelo\Nelo\Saved" "E:\Lightling\Save Games\Steam Games\Nelo\Saved"

mkdir "C:\Users\Lightling\AppData\Roaming\HelloGames"
mklink /j "C:\Users\Lightling\AppData\Roaming\HelloGames\NMS" "E:\Lightling\Save Games\Steam Games\NMS"

mkdir "E:\Lightling\Libraries\Saved Games\Frontier Developments"
mklink /j "E:\Lightling\Libraries\Saved Games\Frontier Developments\Planet Coaster" "E:\Lightling\Save Games\Steam Games\Planet Coaster"

mkdir "E:\Lightling\Libraries\Saved Games\Arkane Studios"
mklink /j "E:\Lightling\Libraries\Saved Games\Arkane Studios\Prey" "E:\Lightling\Save Games\Steam Games\Prey"

mkdir "C:\Users\Lightling\AppData\LocalLow\SomaSim"
mklink /j "C:\Users\Lightling\AppData\LocalLow\SomaSim\Project Highrise" "E:\Lightling\Save Games\Steam Games\Project Highrise"

mkdir "E:\ProgramData\Steam Games\steamapps\common\Rise to Ruins"
mklink /j "E:\ProgramData\Steam Games\steamapps\common\Rise to Ruins\profiles" "E:\Lightling\Save Games\Steam Games\Rise to Ruins\profiles"

mklink /j "C:\Users\Lightling\AppData\Roaming\SpaceEngineers" "E:\Lightling\Save Games\Steam Games\SpaceEngineers"

mklink /j "C:\Users\Lightling\AppData\Roaming\StardewValley" "E:\Lightling\Save Games\Steam Games\Stardew Valley"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Terraria" "E:\Lightling\Save Games\Steam Games\Terraria"

mklink /j "D:\Games\Steam Games\steamapps\common\Morrowind\Saves" "E:\Lightling\Save Games\Steam Games\TES III\Saves"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Oblivion" "E:\Lightling\Save Games\Steam Games\TES IV"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Skyrim" "E:\Lightling\Save Games\Steam Games\TES V"

mkdir "C:\Program Files (x86)\Steam\userdata\114217869\379610"
mklink /j "C:\Program Files (x86)\Steam\userdata\114217869\379610\remote" "E:\Lightling\Save Games\Steam Games\Valley\remote"

mklink /j "E:\Lightling\Libraries\Documents\The Witcher 3" "E:\Lightling\Save Games\Steam Games\Witcher 3"

mkdir "E:\Lightling\Libraries\Saved Games\MachineGames\Wolfenstein The New Order"
mklink /j "E:\Lightling\Libraries\Saved Games\MachineGames\Wolfenstein The New Order\base" "E:\Lightling\Save Games\Steam Games\Wolfenstein - TNO\base"

mkdir "E:\Lightling\Libraries\Saved Games\MachineGames\Wolfenstein The Old Blood"
mklink /j "E:\Lightling\Libraries\Saved Games\MachineGames\Wolfenstein The Old Blood\base" "E:\Lightling\Save Games\Steam Games\Wolfenstein - TOB\base"



REM GOG

mklink /j "C:\Users\Lightling\AppData\Local\AvenColony" "E:\Lightling\Save Games\GOG Games\Aven Colony"

mklink /j "E:\ProgramData\GOG Games\Dungeon Keeper Gold\SAVE" "E:\Lightling\Save Games\GOG Games\Dungeon Keeper\SAVE"

mklink /j "E:\ProgramData\GOG Games\Dungeon Keeper 2\Data\Save" "E:\Lightling\Save Games\GOG Games\Dungeon Keeper 2\Save"

mklink /j "E:\ProgramData\GOG Games\Fallout\DATA\SAVEGAME" "E:\Lightling\Save Games\GOG Games\FO 1\SAVEGAME"

mklink /j "E:\ProgramData\GOG Games\Fallout 2\data\savegame" "E:\Lightling\Save Games\GOG Games\FO 2\savegame"

mklink /j "E:\ProgramData\GOG Games\Fallout Tactics\core\user" "E:\Lightling\Save Games\GOG Games\FO T\user"

mkdir "C:\Users\Lightling\AppData\LocalLow\CampoSanto\Firewatch"
mklink /j "C:\Users\Lightling\AppData\LocalLow\CampoSanto\Firewatch\saves" "E:\Lightling\Save Games\GOG Games\Firewatch\saves"

mklink /j "E:\Lightling\Libraries\Documents\My Games\FasterThanLight" "E:\Lightling\Save Games\GOG Games\FTL"

mkdir "C:\Users\Lightling\AppData\LocalLow\Team Cherry"
mklink /j "C:\Users\Lightling\AppData\LocalLow\Team Cherry\Hollow Knight" "E:\Lightling\Save Games\GOG Games\Hollow Knight"

mkdir "C:\Users\Lightling\AppData\Local\sirengame"
mklink /j "C:\Users\Lightling\AppData\Local\sirengame\SaveGames" "E:\Lightling\Save Games\GOG Games\Rime\SaveGames"

mklink /j "E:\ProgramData\GOG Games\Star Wars - KotOR\saves" "E:\Lightling\Save Games\GOG Games\SW - KOTOR\saves"

mklink /j "E:\ProgramData\GOG Games\Star Wars - KotOR2\saves" "E:\Lightling\Save Games\GOG Games\SW - KOTOR2\saves"

mklink /j "C:\Users\Lightling\AppData\Roaming\Surviving Mars" "E:\Lightling\Save Games\GOG Games\Surviving Mars"

mkdir "C:\Users\Lightling\AppData\Roaming\Nightdive Studios"
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

mkdir "E:\Lightling\Libraries\Documents\Paradox Interactive"
mklink /j "E:\Lightling\Libraries\Documents\Paradox Interactive\Stellaris" "E:\Lightling\Save Games\GOG Games\Stellaris"

mklink /j "E:\Lightling\Libraries\Documents\The Witcher" "E:\Lightling\Save Games\GOG Games\Witcher"

mklink /j "E:\Lightling\Libraries\Documents\Witcher 2" "E:\Lightling\Save Games\GOG Games\Witcher 2"

mklink /j "E:\Lightling\Libraries\Documents\The Witcher 3" "E:\Lightling\Save Games\Steam Games\Witcher 3"



REM ORIGIN

mkdir "E:\Lightling\Libraries\Documents\BioWare"
mklink /j "E:\Lightling\Libraries\Documents\BioWare\Anthem" "E:\Lightling\Save Games\Origin Games\Anthem"

mkdir "C:\Users\Lightling\AppData\Local\Criterion Games"
mklink /j "C:\Users\Lightling\AppData\Local\Criterion Games\Burnout Paradise Remastered" "E:\Lightling\Save Games\Origin Games\Burnout Paradise Remastered"

mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect" "E:\Lightling\Save Games\Origin Games\Mass Effect"

mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect 2" "E:\Lightling\Save Games\Origin Games\Mass Effect 2"

mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect 3" "E:\Lightling\Save Games\Origin Games\Mass Effect 3"

mklink /j "E:\Lightling\Libraries\Documents\BioWare\Mass Effect Andromeda" "E:\Lightling\Save Games\Origin Games\Mass Effect Andromeda"

mkdir "E:\Lightling\Libraries\Documents\Respawn"
mklink /j "E:\Lightling\Libraries\Documents\Respawn\Titanfall2" "E:\Lightling\Save Games\Origin Games\Titanfall2"

mkdir "E:\Lightling\Libraries\Documents\Electronic Arts"
mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 3" "E:\Lightling\Save Games\Origin Games\TS 3"

mklink /j "E:\Lightling\Libraries\Documents\Electronic Arts\The Sims 4" "E:\Lightling\Save Games\Origin Games\TS 4"




REM EGS

mklink /j "E:\Lightling\Libraries\Documents\Darkest" "E:\Lightling\Save Games\EGS\Darkest"




REM OTHER

mklink /j "E:\Lightling\Libraries\Documents\My Games\0ad" "E:\Lightling\Save Games\Other Games\0ad"

mklink /j "C:\Users\Lightling\AppData\Roaming\.minecraft" "D:\Games\Mojang\.minecraft"
mklink /j "D:\Games\Mojang\.minecraft\saves" "E:\Lightling\Save Games\Other Games\Minecraft\saves"

mkdir "C:\Users\Lightling\AppData\LocalLow\Daggerfall Workshop"
mklink /j "C:\Users\Lightling\AppData\LocalLow\Daggerfall Workshop\Daggerfall Unity" "E:\Lightling\Save Games\Other Games\DF - Unity"

mklink /j "E:\Lightling\Libraries\Documents\My Games\Halo" "E:\Lightling\Save Games\Other Games\Halo"

mkdir "C:\Users\Lightling\AppData\Local\Microsoft"
mklink /j "C:\Users\Lightling\AppData\Local\Microsoft\Halo 2" "E:\Lightling\Save Games\Other Games\Halo 2"

mklink /j "E:\Lightling\Libraries\Documents\Halo CE" "E:\Lightling\Save Games\Other Games\Halo CE"

mklink /j "E:\Lightling\Libraries\Documents\OpenRCT2" "E:\Lightling\Save Games\Other Games\OpenRCT2"

mklink /j "E:\Lightling\Libraries\Documents\RCT3" "E:\Lightling\Save Games\Other Games\RCT3"

```