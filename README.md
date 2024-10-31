# Sulfur game
<a href="https://store.steampowered.com/app/2124120/SULFUR/" title="Sulfur">Steam page</a>

Sulfure Crafting Recipes

Game version: 0.9.3

### I2Languages.json
Contains all language references from the game.

### id.sql
Contains mysql database with all Unity IDs of the game resources.

### Recipes folder
Contains recipes in json.

### output.txt and output_ru.txt
Contains (almost) complete list of game recipes in ENG and RU languages.

# How to use
 - Take the recipe file you need.
 - Get the ID of the output item (json path: $.m_Structure.createsItem.m_PathID)
 - Find the corresponding item name in Unity IDs database.
 - Find the corresponding translation of item name in I2Languages.json
 - Repeat steps for every input item ($.m_Structure.itemsNeeded[id].item.m_PathID)