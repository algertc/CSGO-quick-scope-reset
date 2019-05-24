# CSGO-quick-scope-reset
Thank you for downloading this simple CS:GO AWP/Scout Scope Reset Macro



Requirements:
1)  autohotkey
2)  Additional mappable mouse buttons

______________________________________________________________________________________________________________________________________________________________
Instructions:

There are two ways to use this script

1) (easier)

set your knife keybind to x then your primary keybind to E. (within cs)
go into your mouse driver and map a button of your choice to pageup and save (If you would prefer to just use xbutton see slightly more complex version below.)
once you have done this, run the .ahk and get an awp or ssg
shoot, then immediatly after, click the mouse button you mapped. This will quickly reset your scope 


2) (slightly more complex)

If you dont like these keybinds, have existing ones that you prefer, or simply prefer to use qq to quickly switch, Replace "x" and "e" with your desired keys.

Example:

PgUp::
Send,(knife keybind)
Sleep,10
Send,(primary weapon keybind)
return

If you cant remap your mouse buttons or simply dont want to, change pgup to your mouse button (this will look something like {Xbutton #}) A full list of the mouse button identifiers can be found here. --- https://autohotkey.com/docs/KeyList.htm --- 
NOTE: AHK only supports 2 side mouse buttons. If you have 3 (steelseries rival, Razer naga ect) and want to use one of the additionsal buttons, map it to page up within the mouse driver.

Example of the script without using pgup

Xbutton#::
Send,x
Sleep,10
Send,e
return
