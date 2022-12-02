# Index Card RPG: Master Edition - Official Foundry VTT Module
Public issue tracking and documentation for the ICRPG: Master Edition FVTT premium content

## What's included
- 16 Journal entries, from the 400 pages of the book. Each page has been optimized for Foundry VTT
- More than 1400 Items, each linked directly into the Journals. Easily import items in your characters with simple drag and drop!
- 70 Actors with complete ARTWORK and TOKENS
  - 6 vehicles
  - 12 villains
  - 4 megafauna
  - 48 monsters
- 60 tables
- More than 300 artwork images from the book, optimized to .webp format to reduce loading times
- 19 ready to use Scenes
  - 4 high quality world maps
  - 3 warp shell interiors
  - 12 dungeons

## How to install
1. Find where your Foundry Module Data is stored. [Where is my data stored?](https://foundryvtt.com/article/configuration/#:~:text=Where%20Is%20My%20Data%20Stored%3F). By default:
  - Windows: `%localappdata%/FoundryVTT/Data/modules`. To go there quickly, you can press Windows+R, paste `%localappdata%/FoundryVTT/Data/modules` and press enter. Alternatively you can manually browse the folder, which is located at: `C:\Users\<YOUR_USER_NAME>\AppData\Local\FoundryVTT\Data\modules`
- macOS:  `~/Library/Application Support/FoundryVTT/Data/modules`
- Linux: `/home/$USER/.local/share/FoundryVTT`, `/home/$USER/FoundryVTT`, `/local/FoundryVTT`

2. After locating where your Foundry install is located, extract the content of the module's zip. After extracting, the modules folder structure should be:
```
FoundryVTT/Data/modules/
├─ icrpg-premium-content/
│  ├─ module.json
│  ├─ assets/
│  ├─ module/
│  ├─ packs/
│  ├─ styles/
```
Note: the extracted folder's name in FoundryVTT/Data/modules/ must be icrpg-premium-content!

3. You are all set! Restart your foundry application and enable the module in your game settings.

#### Installing on The Forge
You can install this module using the "Import Wizard" and selecting the .zip. You can refer to [this guide](https://forums.forge-vtt.com/t/how-to-upload-a-modified-version-of-a-module-system/10510) for further details.

## How to use
The module includes 8 item compendiums and 1 adventure compendium. 

#### Item Compendiums
The _Item_ compendiums are divided by world or book chapter (Alfheim, Warp Shell, Paths, Ghost Mountain, Vigilante City, Blood and Snow, Magic and Tables). 

#### Adventure Compendium
The _Adventure_ compendium "Index Card RPG: Master Edition" includes:
- the ICRPG book Journals in the "ICRPG: Master Edition" adventure.
- the Monsters adventure, containing 48 ready to use Actors from the Monsters section
- an adventure for each world or book chapter. Those adventures can include: ready to use Tables, Monsters and Scenes
<p align="center">
<img src="https://raw.githubusercontent.com/ClipplerBlood/icrpg-premium-content/main/screens/compendiums.png" width="500">
</p>


##### Importing an adventure
To import an adventure, open the adventure item inside the compendium, and press the "Import Adventure" button.
<p align="center">
<img src="https://raw.githubusercontent.com/ClipplerBlood/icrpg-premium-content/main/screens/adventure.png" width="500">
</p>

### Content links and item organization
In the ICRPG journals, all items present in the book are _linked_ to their respective compendium entry. When hovering on an item name, you can see that its background and color changes indicating that it is a link. With links you can:
- Click on them to open the Item sheet
- Drag the link in the Character sheet to quickly add it to the character

<p align="center">
<img src="https://raw.githubusercontent.com/ClipplerBlood/icrpg-premium-content/main/screens/dragging.gif">
</p>

