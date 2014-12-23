OS X Handmade Hero
==================

This is an ongoing OS X port of Casey Muratori's Handmade Hero.

This version uses native OS X libraries for the platform layer:
- CoreAudio for sound
- OpenGL for graphics
- IOKit's HID for joystick input

The goal is to be able to drop in Casey's platform independent
game source code and compile and run it unchanged.

This Xcode project first builds a dynamic library subproject
called libhandmade.dylib and includes it in the Handmade Hero
product directory of the application bundle.



IMPORTANT
---------
I removed Casey's platform-independent game code from this
repository. At the moment that is just handmade.cpp and 
handmade.h.

Once you clone or update from this repository, copy over the
handmade.cpp/.h files from Casey's source code to the handmade
subdirectory.

This repository works with Casey's handmade.cpp/.h files from
handmade_hero_025_source.



Author
------
Jeff Buck

The original version of Handmade Hero is being created by Casey Muratori.

You can find more information about Handmade Hero at:
	http://handmadehero.org


