# Pokemon Anil Random - English
This mod pack was created by @joelkm (https://twitter.com/JoelMustDeploy), this is just an English adaptation and instruction set made for a discord community. Please see https://github.com/joelkm/PokemonAnilRandom for the original work.

## 
All restrictions from the original randomizer remain as of now.

Randomizor Options:
✔️ Pokemon skills
✔️ Pokemon moveset (both egg and level)
✔️ Wild encounters
✔️ Drops de pokemon salvajes (Los que tienen) // Wild Pokemon Drops (The Haves) [[ need better translation for this bullet point ]]
✔️ Pokemon Trainers
✔️ Pokemon Trainers' Combat Items
✔️ Mega coaches [[ I'm out of the pokemon loop so I think this sounds right based on what I know of mega evolution ]]
✔️ TMs
✔️ Move Reminders

✖️ Starter Choice
✖️ Raids
✖️ Pokemon Mega Abilities
✖️ World Items  // (Para no cargarme misiones de historia)
✖️ Move Tutors
✖️ Fossils
✖️ Trading NPCs

Other details:
- All trainers over lvl 36 have fully evolved pokemon
- Rebalanced Pokeball prices:
    - Pokeball 200
    - Greatball 800
    - Ultraball 1500
    - All Others 2500
-Superguard/Wonderguard removed
-Going to start with the gen9 moves removed unless it's more work to remove it, add it in if requested
-TM108 is empty (It's not intentional, the original TM of Metronome does weird things and stays that way). [[ need better translation ]]


## Installation and Runtime Instructions

### Prerequisites
- Windows
- [Node.js](https://nodejs.org/en/download)
- RPGMakerXP
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

## Goals
- Remove RPGMaker XP Requirement
  - Incorperate Randomizer as another Game Mode at Classic/Complete/Radical selection or some other easily accessible way
- Improve translations
- Add QoL features

