# byHaviour
## What is it?
byHaviour is a free **Minecraft:Bedrock Edition behaviour pack editor** written in Python. You can edit everything to-do with Behaviour Packs with a clean minimalist interface. 

## Why use it?
byHaviour helps you significantly speed up your workflow when working with behaviour packs. 

It is in essence a tailor made JSON editor, designed to be used to edit entity, loot and trade table files, although supports all JSON files. The joy of working with a JSON editor is that you have no worry of syntax errors.
It includes smart and dynamic suggestions and autocompletion meaning you can write entitre files with ease and just a few key presses. 
You can also load packs, bringing up an overview page with a handy list of all entities in the pack.

## Features
 - **Smart and Dynamic Suggestions**
   - Components, Subcomponents, Filters, Condition, Functions, Loot, Trades all autocomplete.
   - Suggests component groups and events referenced elsewhere in the file.
   - Builtin lists of items, blocks and entities.
 
 - **Simple but Powerful Editor**
   - Entities are split into 3 subeditors: "Component Groups", "Components" and "Events" leading to a clear and organised workspace.
   - Highlight keywords in your file.
   - Copy and directly paste JSON into the editor.
   - Reorder objects and interact with the editor using shortcuts.
 
 - **Behaviour Pack Overview Tab**
   - Change the pack icon and edit the manifest file.
   - View all entities used in your pack, and see those that are not!
   - Set a frequently edited pack as default so you can quickly open and edit files.
 
 - **Light and Dark Theme**
   - A light, vibrant theme for those excited to create behaviour packs!
   - A dark theme for Marketplace mechanics.
   
 - **Prewritten Components**
   - Press a button or use shortcuts to import prewritten components into your files.
   - You can easily add other frequently written components, outlined [here](#prewritten-components).


## Screenshots
### Overview
![Light Overview](https://github.com/byAdam/byHaviour/blob/master/images/overviewLight.png)
![Dark Overview](https://github.com/byAdam/byHaviour/blob/master/images/overviewDark.png)
### Editor
![Light Editor](https://github.com/byAdam/byHaviour/blob/master/images/editorLight.png)
![Dark Editor](https://github.com/byAdam/byHaviour/blob/master/images/editorDark.png)
![Light Suggestions](https://github.com/byAdam/byHaviour/blob/master/images/suggestionLight.png)
![Dark Suggestions](https://github.com/byAdam/byHaviour/blob/master/images/suggestionDark.png)

## Prewritten Components
To add a new component you can import is very simple
1. Create a new JSON file in "/assets/imports/" in the folder with your byHaviour.exe file.
2. Copy the template found [here](importTemplate.json).
3. Change the value of "name" to the name you want in the imports menu
4. Change the value of "data" to the component(s)
5. Change the value of "priority" depending where you want it in the imports menu
