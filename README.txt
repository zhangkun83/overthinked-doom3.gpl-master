Overthinked Doom 3 Linux buildable source
=========================================

This is the source code forked from the Overthinked Doom 3 mod. I
changed it to be buildable on Linux.

How to build
------------

A possibly incomplete list of dependencies (named per Ubuntu packaging):
- libssl-dev:i386
- byacc
- libX11-dev:i386
- libxext-dev:i386
- libxxf86vm:i386

```
$ cd neo
$ scons
$ cp doom.x86 <your-doom3-dir-that-contains-base>
$ cp gamex86-base.so <overthinked-dir>/gamex86.so
```
