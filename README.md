# Honeycomb
Honeycomb Macropad resources

Same build guide just with pictures on google doc
https://docs.google.com/document/d/14a2hFu1UxXCSy6_h_vsCM83b5FNv_yJvU5wKORFzzPQ/edit?usp=sharing


Make sure you know how to solder
Watch this video: https://youtu.be/5uiroWBkdFY 
Do not skip this part unless you have done SMD soldering before. This video is super helpful.
Remember to take your time during building, this isn’t a race and you don’t get points for finishing early.
I DON’T HAVE EXTRAS. One sec, lemme say that again: I DON’T HAVE EXTRAS. If you mess this up, you’re going to have to source the parts yourself.
I make no guarantees unless it was clearly my fault. If you mess up the board in any way, I am very sorry but there’s only so much I can do.
Lots of pics here: https://imgur.com/a/CEj04Fa 
Receiver
SMD stuff. This is the trickiest part of the board
The tiny 8 pin thing: Do this first in case you mess up. Take a chisel tip and do a little bit of solder at a time. Apply a little bit of solder to the pads ahead of time. 
4 pin: add a bit of solder to the pads. Do the single big pin first, then the 3 smaller ones. Reflow the solder as needed
Through hole:
Capacitors: Add the yellow capacitors next to the small 8 pin
Resistors: Pay attention to the pictures. Certain stripes go in certain locations.
Sockets: This is the easiest part of the board and is essential in my opinion. Makes it so much easier to fix later if something went wrong. Just stick the sockets in and solder. The two row sockets can be a little tricky. Just make sure you have the right angle to not get solder on other pins or bridge them.
Empty slots:
The empty slots are for troubleshooting. You can add an LED, 4 pin header, and a reset button. None of them are needed.
Board
SMD Stuff
NRF Chip: Once again, do this first. It is the hardest part on this PCB. Make sure you watched the video I linked above. Start by doing corners if you can. Make sure you use a chisel tip if you can. You don’t need much solder.
3 pin: Like on the receiver, do the big pin first and then the little ones.
Battery holder. Add a bit of solder to both sides. Add the holder. Solder one side at a time.
Hotswap sockets: Like with the battery, add a little bit of solder to all the pads. Solder one side at a time, holding it in place with a finger or tweezers. The socket should be flush with the pcb.
Through Hole:
Resistors. This part should be straightforward. Put one of each resistor in the slot on the same side as the sockets. It helps if you solder the resistors from the top. Clip the legs afterward. 
Rotary encoder: You’ll need to either cut off the stabilizing legs or trim them. For some reason the ones I got have too big of legs. These legs are non-essential. There are 5 pins on the encoder. They should line up with the other holes. Make sure you put it on the opposite side of the sockets.
Everything else:
Switches: Just add switches. It’s easy if you clip them into the plate and then just slowly put the plate on, careful not to bend any of the switch legs. You can also just put the switches in one-by-one. 
Battery: Add a coin cell CR-2032 3v battery. I did not provide one because of shipping regulations. You can find them at any corner store or wal-mart equivalent.
Plug it in
All that is left is for you to plug in your pro micro and flash the layout. You should be able to find it in QMK under “Honeycomb”
Once it is flashed it should work right away.
Troubleshoot
A good guide to troubleshooting another keyboard that uses the same system: https://hackaday.io/project/160704-dichotomy-keyboard-and-mouse/log/157597-debugging-the-receiver

