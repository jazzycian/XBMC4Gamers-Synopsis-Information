# XBMC4Gamers-Synopsis-Information

Synopsis now installed via the xbmc4gamers and xbmc-emustation artwork installer scripts from within the dashboards download menu. This synopsis will work with xbmc origins also. Boot xbmc4gamers or xbmc-emustation and run the artwork installer or drop resources folders into your game folders manually. This is uploaded here for information and possible future projects by other people.

Synopsis information for use with Rocky5's sublime XBMC4Gamers. These synopsis should be compatible with any XBMC 3.5.3 or above build once Rocky5's custom synopsis script and custom XBMC xbe are used. 

Download the relevant zip for a HDD ready XBMC4Gamers Synopsis information setup. There is now emulator, homebrew and xbox synopsis. Transfer each resources folder to the root of your respective game/emulator folder on your Xbox or if you already have resources folders place the respective 'default.xml' in the root of your _resources folder for each title. Resources folder/file structure example can be found on Rocky5's XBMC4Gamers Github.

Excel spreadsheets included with the most complete list of information for the complete Original Xbox worldwide games list. This was built from many online sources and defunct websites using the wayback machine. Version 3 was refined by taking information from the back of the game folders. You can filter the spreadsheet by ratings, genre etc. It is a good tool for finding good/bad games. The primary building block for this spreadsheet originally was Cameron Brigmans EmuExtras list of Original Xbox games. Rocky5 created batch tools to bulk extract them from the original Excel to xml export. One batch file is intended for cover position coding at the end of the folder names, -T, -M, -B, -MB, -MT. (T = Top, M = Middle, B = Bottom, MB = Middle Bottom, MT = Middle Top). This coding is used by the artwork installer script and is there for that purpose. If you are generating synopsis manually use the batch tool that is not for position coded names.

If anyone wants to get involved and translate the synopsis to another language please translate the Excel or XMLs with the complete list inside. Prefereably the Excel and it can be added here if there any complete translations.

For each set I have included the original Excel spreadsheet with XML mapping, the exported XML that has the entire exported list, the batch tools to break the synopsis out to individual folders/files and the final product already exported for convenience. 

The PDF instructions are from the previous version but are still correct except a few things. I may update them at some point.

1. You need to drag the XML on to the .bat file to run it.
2. You will need to delete some jargon from the line 2 at the top of the XML if you export your own so it just reads <synopsis_Map>. If you don't do this the .bat file will not work.
3. In the NTSC section Zillernet won't batch out as it has brackets in the name - Zillernet (Korea). It will just be made as a default.xml beside the generated folders. Add it manually if needed.

Enjoy!!!

