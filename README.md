# inDot
A project that aims to convert Godot 4 (and maybe Godot 3) projects to SDL 1.2, which can run on systems that don't support OpenGL 3.3 and can run on systems as old as Windows 95 (although my focus is to run it on Windows 98).

# How it will work
The code will most likely be written in Python. Firstly, the game's assets will be extracted into 4 folders: images, audio, code, and etc. The code will then be converted into C++, along with having a provided `godot.h` that houses Godot's functions (e.g., Input, etc). Also, these project can be converted to have either OpenGL 1.1 or even software rendering.

# Why?
When I make video games, I want to try to make them accessible to many people as possible.
Also because it's fun.

# TODO
- [ ] Work on the code
