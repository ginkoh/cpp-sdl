# cpp-sdl

## How to run it on Visual Studio

- Download SDL2-devel-x.x.xx-VC.zip development library
- Go to: Project Properties > Configuration Properties > VC++ Directories > Include Directories > and add SDL "include" folder, and into "Library Directories" add the SDL lib x64 folder.
- Go to: Project Properties > Configuration Properties > Linker > Input > Additional Dependencies and add two lines:
  > SDL2.lib  
  > SDL2main.lib
- Change the project compiler from debug x86 to release x64
