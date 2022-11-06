# NovetusFE-WS
NovetusFE Workshop Store, stores information for the workshop. NovetusFE development has been halted, however you are welcome to fork NovetusFE and create a standalone workshop viewer if you wish. You could create it in a different programming language, if you know your way around json files and github's api. 
## This should go without saying anything, but you should probably be careful when downloading anything that isn't from Bitl.
I had to include this because clients are being added to the Workshop and I don't have any way to verify if they could be malware or not.

# Rules
Since Novetus is quite a small community I doubt that a huge number of commits is going to happen, so we should be fine for now. However, I still have rules, No malware, no attempts at griefing, no nsfw or lewd addon icons. If you break one of these rules I will not add your project or mod to the workshop and if you get a project added but break rules after then I will remove your project from the workshop and never add it back.

# Example
store.json
```
{
	"shortname":"CharCommands",
	"longname":"Character Commands",
	"description":"Robloxian 2.0 Addon for Novetus",
	"creator":"Lachrymogenic",
	"tags":["addons"],
	"url":"https://github.com/Lachrymogenic/CharacterCommands/archive/refs/heads/main.zip",
	"iconurl":"https://raw.githubusercontent.com/Lachrymogenic/CharacterCommands/main/charcustom.png",
	"leaveout":true
}
```    
# How to add your Project / Mod to the Workshop?
See the legend for the list of JSON keys and what they do.

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
## leaveout
If you are using Github, set this to true, as leave out will take the first folder in a zip file and treat it as if it were the root folder, if everything is correctly in the root of the zip file, and the structure is ./addons and not ./Project-main/addons, then you can set this to false, bool.
