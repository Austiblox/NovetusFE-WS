# NovetusFE-WS
NovetusFE Workshop Store

# Example
store.json
[code]
       {
				"shortname":"CharCommands",
				"longname":"Character Commands",
				"description":"Robloxian 2.0 Addon for Novetus",
				"creator":"Lachrymogenic",
				"tags":["addons"],
				"url":"https://github.com/Lachrymogenic/CharacterCommands/archive/refs/heads/main.zip",
				"iconurl":"https://raw.githubusercontent.com/Lachrymogenic/CharacterCommands/main/charcustom.png",
				"indexlocation":"CharacterCommands-main/index.txt",
				"leaveout":true,
			},
[/code]      
index.txt
[code]
CharacterCommands-main/addons/CharacterCommands.lua
[/code]

# How to add your Project / Mod to the Workshop?
First, create an index.txt file for your mod / project, this file will contain a list of every file you wish to be extracted from within a zip file. For an example of how to create an index.txt, see my example project here, https://github.com/Lachrymogenic/CharacterCommands The format is usually "modname-main/(addons / models / sounds / whatever)/(if you have extra folders: folder-name / )your-file Make a commit to store.json and make sure you format it correctly, do not forget commas etc.

# Legend
## shortname
A shortname is a short name for the Compact theme of NovetusFE, string.
## longname
A longname is a long name for an Extended theme of NovetusFE, string.
## description
A description for your mod / project, string.
## creator
The creator of the mod / project, string.
## tags
Search tags to make finding your mod / project easier, (e.g "addons" or "place" or "models" or "themes"), strings in array.
## url
The URL which NovetusFE will use to download your mod / project, string.
## iconurl
The URL which NovetusFE will use to download your mod / project's Icon. (128x128), string.
## indexlocation
Location of index.txt inside of the zipfile, string.
## leaveout
If you are using Github, set this to true, as leave out will take the first folder in a zip file and treat it as if it were the root folder, if everything is correctly in the root of the zip file, and the structure is ./addons and not ./Project-main/addons, then you can set this to false, bool.
