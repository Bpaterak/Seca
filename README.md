# Seca

Your friendly Sketch slicing helper.

## How to install
1. Download and open [Seca-master.zip](https://github.com/iGenius-Srl/Seca/archive/master.zip)
2. Open ```Seca.sketchplugin``` (Sketch will magically install the plugin)

## Wha's new
* 1.0.0 updated export for ios
* 1.0.0 support for web, export always in 2x
* 0.0.3 file names formatted for Android framework don't create unnecessary folders when exporting files

  Export(Android & iOS & Web ) of an icon named `09£%-_--Icons/Symbols/Dark/Right` from page `⌘ Icons`
  
```
 |- Android
    |- Icons
        |- drawable-*
            |- n09_icons_symbols_dark_right.png
     
 |- iOS
    |- Icons
       |- n09_icons_symbols_dark_right.imageset
          |- Contents.json
          |- n09_icons_symbols_dark_right.png 
          |- n09_icons_symbols_dark_right@2x.png 
          |- n09_icons_symbols_dark_right@3x.png 
 |- Web
     |- 09£%-_--Icons
        |- Symbols
          |- Dark
            |- Right.png
```
  The top level has been decided to be left in case you need to distinguish between assets in different pages
  
* 0.0.2
  page name strip of not unicode characters
* 0.0.1
  create a wrapper folder based on the page name, remove error prone exporting options ( not complete ios and Android export )

## Notes
* Tested on Sketch 43.1
