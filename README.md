# 3D /me and /do
The /me and /do command but it's 3D printed with different colors.
ALL credits to Sheamle/3dme, known as Elio on FiveM - they made/released this, I just edited it to add /do.
<img src=https://i.imgur.com/vaNE2Ip.png>

## Installation
* Download the resource ;
* Drag and drop it into your resources folder ;
* Add ```start 3dme``` to you ```server.cfg```.

## How to use
* In the chat, type /me or /do followed by your action.

## Options 
* Color of the text : ```client.lua``` line 14 : ```local color = { r = 230, g = 230, b = 230, a = 255 }```
* Font of the text : ```client.lua``` line 15 : ```local font = 0``` Available fonts : https://imgur.com/a/oV3ciWs
* Time on screen : ```client.lua``` line 4 : ```local displayTime = 5000```
