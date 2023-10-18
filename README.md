# Pokémon Añil Randomizer - English
This mod pack was originally created by [joelkm](https://github.com/joelkm) ([Twitter account](https://twitter.com/JoelMustDeploy)). This is an English fork with some additional changes plus updated instructions for the CLA Discord community.

Thank you to Fran, Motch, duckingcreepers and more from the CLA Community for additonal translation, design, and programming work!

## 
All restrictions from the original randomizer remain as of now.

Randomizor Options:
- ✅ Wild encounters
- ✅ Pokemon Trainers
- ✅ Pokemon Trainers' Combat Items
- ✅ Trainers' Megas
- ✅ TMs
- ✅ Move Reminders
- ❌ Starter Choice
- ❌ Pokemon Moves
- ❌ Pokemon Egg Moves
- ❌ Pokemon Abilities
- ❌ Pokemon Hidden Ability
- ❌ Wild Pokemon Held Items
- ❌ Raids
- ❌ Pokemon Mega Abilities
- ❌ Overworld Items (To not mess up main quest line)
- ❌ Move Tutors
- ❌ Fossils
- ❌ Trading NPCs

Other details:
- All trainers over lvl 36 have fully evolved pokemon
- Rebalanced Pokeball prices:
    - Pokeball 200
    - Greatball 800
    - Ultraball 1500
    - All Others 2500
- Superguard/Wonderguard removed
- Going to start with the gen9 moves removed unless it's more work to remove it, add it in if requested
- TM108 is empty (Issue with TM108 - Metronome itself)

## Installation and Runtime Instructions

### Prerequisites
- Windows
- [Node.js](https://nodejs.org/en/download)
- [RPGMakerXP](https://store.steampowered.com/app/235900/RPG_Maker_XP/)
- An unmodified version of Pokemon Anil

#### Installing NPM
1. Download and run the installer from the link above
2. Leave the default Destination Folder, click Next
3. Leave the Custom Setup options alone and click Next
4. Leave the box unchecked on the "Tools for Native Modules" page  and click Next
5. Click Install
6. You will most likely get a Windows Popup asking if you've like to confirm the installation, click Yes
7. Click Finish once it's done installing

#### Folder Structure
The randomizer affects the files of the game itself, so for your sanity (and to avoid messing up your saves) you should maintain a separate folder (i.e. C:\PokemonAnil) where you can easily copy and paste the original (currently Pokemon Anil V1.12) into a new folder and start the randomizer process.

In other words, the data of each run is saved in the game's own folder, so if you want to play several different runs at once, you must repeat the following process in different folders so as not to load your runs.

#### Instructions
1. Move the modpack folder (called "Custom" in the picture example) into the Anil folder you'd like to randomize
2. Move the "Game.rxproj" file from the modpack folder up one level to the root folder of the game. It should look similar to the below image:
![image](https://github.com/joelkm/PokemonAnilModpack/assets/109240974/ce115dfc-ab56-4208-9180-831784965595)
3. Click "auto-randomize" in the modpack folder. This will keep you from having the think about the Command Prompt at all.   
8. Open the "Game.rxproj" file. RPGMaker will open and you will have a screen like this in front of you:
![image](https://github.com/joelkm/PokemonAnilModpack/assets/109240974/a3fff0d9-ccd4-42bd-86a5-e6fddde2577b)  
9. Click on the green triangle in the menu: 
![image](https://github.com/joelkm/PokemonAnilModpack/assets/109240974/b3d0d0be-ec3e-4b79-a300-74da60add3be)  
A new black window running the game will open, you'll see the name of the window change to "Compilando", "Procesando datos de ...", etc.
![image](https://github.com/joelkm/PokemonAnilModpack/assets/109240974/0cd9a957-7495-40ea-b24c-ebeef90996af)  
The name will change until the process is finished. Once completed, the game will open automatically with everything randomized.

Open "Game.exe" and enjoy!

