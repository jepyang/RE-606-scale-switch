# RE-606-scale-switch

In this repository you will find all the materials needed to recreate Jepyang's RE-606 scale switch replacement.

There are two sets of gerber files, you will need to have both made into PCBs. I like Osh Park for small runs of tiny PCBs like this, but any manufacturer is probably fine.

You also need to buy switches. SS24h01 is the generic part name, and they can be purchased from multiple suppliers. Be aware that there are multiple handle styles for this switch, and getting the right one is important for constructing the replacement switch. Ideally, you want the version with a cylindrical handle—I've seen this type listed as SS24h01 NAT5, but sometimes it's still listed without the extra suffix. I got mine here: https://www.electronicsurplus.com/wmc-ss24h01-nat5-switch-slide-contacts-dp4t-dc-4-position but I've also seen similar ones for sale on eBay and aliexpress. The switch cap STL file for 3D printing is sized for the cylindrical handle (and the switch cap is actually necessary for clearing the front panel enough to be functional; not simply aesthetic). Alternatively, there also exists a long-handled version of the switch, which should clear the front panel without any kind of cap. Unfortunately, this style is somewhat hard to find without ordering a large minimum quantity, but if you run into it, it'll work fine. The standard short, square/rectangular handle will not work—you may be able to design and 3d print a different switch cap but that's on you.

And lastly, you also need some standard, single-row 2.54mm pitch pin headers. You need two seven-pin lengths to connect the two boards, and you need fourteen individual pins to go between the bottom board and the RE-606.

# NOTE
The "complete.jpg" image is for assembly reference, but is a photo of an earlier revision of the switch. Two things to note.

One, the photo shows only five pins on each side going between the two PCBs; the final revision has seven pins. The additional two pins on each side are dummy pins only, just there to add mechanical stiffness.

Two, the photo shows the 14 individual pins at the bottom of the switch with their little plastic sheathes still on. You should solder them like this, but for the RE-606 case you'll need to pull off all those little plastic things after soldering—otherwise the switch assembly will not fit under the 606 switch board. Basically, you want the bottom adapter board near to flush with the RE-606 PCB. (This also means you need to trim the excess from the pins that connect the two adapter boards.) I suspect that in a real 606 case, you'll want to leave the plastic bits on, but I cannot personally confirm this as I dont have a real 606 case to test. Please double-check before installing in anything but the RE-606 metal case.
