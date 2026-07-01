# Compact_Pheal
Aardwolf MUSHCLIENT plugin to reduce party heal spam.  
Condenses all party healing in and out into one line, either on a set timer (default) or at every prompt - only works on default prompt style [...>

Place Compact_Pheal.xml in your plugins folder and add it using the Plugins menu (CTRL+SHIFT+P).  
Place waka-waka.wav in your sounds folder. Or don't.

Commands:  
cpheal help  
cpheal on/off [default on]  
cpheal timer -> displays timer status 
cpheal timer on/off  -> switch between timer and prompt display [default on]  
cpheal timer # -> set timer in seconds [default 5]  
cpheal pacman on/off -> toggle omission of blank lines between received pheals [default on]  
cpheal sound on/off -> toggle waka-waka [default off]  
cpheal test on/off -> toggle test mode [default off]  

TODO: 
- configurable prompt trigger?
