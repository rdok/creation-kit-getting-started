# Skyrim Creation Kit
### Chapters
#### [1. Getting Started](https://www.creationkit.com/index.php?title=Category:Getting_Started)
This first chapter goes  over the basics of getting up and running with the Creation Kit:
- How to install the Creation Kit
- How to create and save a plugin (main mod data file)
- How to load a plugin into the game  

#### [2. Bethesda Tutorial Creation Kit Interface ](https://www.creationkit.com/index.php?title=Bethesda_Tutorial_Creation_Kit_Interface)

### Link mod with git repo
We need to create a hard link to the mod we want to work with. This allows us
to link the mod we want to work with with this Git repository.

#### Template
```
mklink /H "D:\Code\fallout-4-creation-kit\{Working Chapter}\{Mod Name}.esp" "D:\SteamLibrary\steamapps\common\Fallout 4\Data\{Mod Name}.esp"
```

#### Usages
```
mklink /H "D:\Code\fallout-4-creation-kit\1. Getting Started\testquest.esp" "D:\SteamLibrary\steamapps\common\Fallout 4\Data\testquest.esp"
```

## Useful Links
- [Configuration Settings](http://wiki.step-project.com/Guide:Skyrim_Configuration_Settings)
- [Skyrim INI](http://wiki.step-project.com/Guide:SkyrimPrefs_INI)
- [Bethesda_Tutorial_Creation_Kit_Interface](http://www.creationkit.com/Bethesda_Tutorial_Creation_Kit_Interface)
   - [Main_Toolbar](http://www.creationkit.com/Main_Toolbar)
   - [Render_Window](http://www.creationkit.com/Render_Window)
   - [Object_Window](http://www.creationkit.com/Object_Window)
