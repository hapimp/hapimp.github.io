# The **Mini MiSTer Arcade** Resource Page
I am gathering all the stuff I can find about the best way to use an iPad 3/4 display in a mini arcade machine, like the iCade.

This page will offer recommendations on what to buy and how to build a mini arcade machine using [MiSTer hardware](https://github.com/MiSTer-devel/Main_MiSTer/wiki) and an iPad 3/4 screen.

This machine is a really nice and low lag solution for retro gaming, with some drawbacks.

This is how my arcade currently looks.
![](pics/mister.jpeg)

## What to buy
To make a MiSTer Mini Arcade you will need an arcade cabinet, a MiSTer, a display, and various bits and pieces to put it all together.

- **MiSTer**: Follow the instructions over on the MiSTer wiki [MiSTer wiki](https://github.com/MiSTer-devel/Main_MiSTer/wiki) to figure out what you need.
- **Joystick and buttons**: I chose to replace the joystick in the arcade cabinet with Sanwa parts. OBSF-30 buttons (8) and the JLF-8YT-SK joystick.
- **Joystick controller board**: You will also need a controller board if you buy arcade joystick and buttons. I chose an [Arduino Pro Micro](https://www.sparkfun.com/products/12640) (you can get clones way cheaper than this, but this one is really good) with the [DaemonBite firmware](https://github.com/MickGyver/DaemonBite-Arcade-Encoder) (a really low lag solution, and not expensive at all).
- **iPad display controller board and PSU**: You need to order [this](https://www.aliexpress.com/item/4000751222618.html) one from Aliexpress. I was told to order the blue one and not the green one, to be sure it is the right one. There are several versions that work, but this has the lowest lag. You can use a 5V micro USB charger to power the display/driver board combo, but you need to find a compatible 12V PSU to get full brightness. At this point I don't have one to recommend.
- **iPad display**: You need to order [this](https://www.aliexpress.com/item/32272565025.html) from Aliexpress (I also think you can salvage it if you have an old iPad 3/4 that is broken, but the display is functional).
- **Mini arcade cabinet**: I found a used ION iCade cabinet for about 50USD.
- **Sound**: Right now I am just using a minijack to minijack to connect the driver board to a powered mono speaker. Would definitely be better to mount stereo speakers in the cabinet somehow.

## Modding it
I modded the iCade somewhat to make it suitable for the MiSTer arcade.

- I removed the plastic holding the iPad, so I could feed the wires fr

- Lidt om de gode og dårlige ting
	- minus kontrolpanel
	- minus kabelmanagement
	- plus man kan bare sætte sit stick i
	- minus rotation
- Om hvordan jeg moddede
	- træplade i bunden
	- Fjernede plastic
	- Udvidede huller
	- Lavede standoffs
	- Monterede skærm på træplade