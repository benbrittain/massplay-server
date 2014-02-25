massplay-server
===============

V1.1 implementation of the massplay game server


About
====
An experiment in multiplayer gameplay of classic roms

Implementation
==============

This is essentially a port of the old virtual boy emululator with a large amount of code ripped out.
The frames are then encoded with vp8 and streamed to all connected parties. Input is recieved via
websockets and injected into the emulator loop.

TODO
====
Essentially all of it. This is a cleaned up version of the hack we implemented at McHacks (which did
not encode video, merely trasmited base64 encoded bitmaps over websockets.


Licensing
=========
Released under GPLv2 since VBA-m, which this is in many ways a port of, is that license. All code
in the /libs folder is that respective projects license (usually more permissive). Any code which
can be successfully determined not to be VBA-m code (and not a library) may be used under MIT.
