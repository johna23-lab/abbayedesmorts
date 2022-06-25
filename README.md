# Abbaye-SDL

This version already has the SDL libraries integrated in the binary and is available for 64 bits (GNU/Linux, glibc 2.27, Ubuntu 18.04/Linx Mint 19.3)

Port of indie game "l'Abbaye des Morts". Originally released by Locomalito to Windows
platform in year 2010.
This port uses C language with SDL libraries.

# Media / Screenshots

[![shot1](https://github.com/nevat/abbayedesmorts-gpl/raw/master/screenshots/title_thumb.png)
[![shot2](https://github.com/nevat/abbayedesmorts-gpl/raw/master/screenshots/title-md_thumb.png)
[![shot3](https://github.com/nevat/abbayedesmorts-gpl/raw/master/screenshots/ingame_thumb.png)
[![shot4](https://github.com/nevat/abbayedesmorts-gpl/raw/master/screenshots/ingame-md_thumb.png)

# Platforms

Currently, this port works on:

  * GNU/Linux (32 & 64 bits), including Raspberry Pi
  * FreeBSD
  * OpenPandora
  * CGW Zero
  * Nintendo Wii

Fell free if you want to port this program to another system, it's opensource, take the
code and modify!

# Installation from source

Under GNU/Linux and FreeBSD, in order to compile this program, you need to install SDL2
libraries. Check your distribution instructions.

Unpack the source code file:

`$ tar xf abbaye_linux_v2_beta.tar.gz`

Enter the directory created an run:

`$ make`

As root, install the game with:

`# make install` (Ubuntu users run: `$ sudo make install`)

An icon will appear in your application menu, in game section.
Alternatively you can run the game with `abbayev2`.

# Uninstallation from source

Enter the directory and run (as root):

`# make uninstall` (Ubuntu users run: `$ sudo make uninstall`).

# History

Abbaye des Morts is a freeware game made by LocoMalito (with the help of Gryzor87 in
music side) in 2010. Was developed with Gamemaker and only runs natively in Microsoft
Windows systems.

This is a port to GNU/Linux systems & any system that supports C and SDL libraries.

The version 2.0 of the game is a port from SDL1.2 to SDL2 libraries. This includes a nice
set of features: OpenGL rendering, auto-scaling, Android & IOS support, VSync, etc.

# License

The code is licensed under GNU GPL version 3, so anyone can download, see, change and
redistribute the code.
