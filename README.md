<center><img width="474" height="374" alt="image" src="https://github.com/user-attachments/assets/387632b6-9baa-453e-858f-171816723476" /></center>

inDot (short for "INfinite GoDOT" formerly known as "Godot98") will be a project that aims to port Godot 4 projects to older devices via SDL 1.2. Right now, the focus of the project is to make Godot games to run under Windows 98SE.

# My Goals (and why)
I want to make video games accessible to all kinds of people. Many people would shun a project like this for being "pointless", but even with that this would be a fun learning experience.
I also want to get into programming into lower level codebases, such as C, C++, and even Assembly.

# How it will work (OUTDATED)
The code will likely be written in Python. Firstly, the game's assets will be extracted into a singular folder, and will convert all WAV files to OGG if necessary The code will then be converted into C++, along with having a provided `godot.h` that houses Godot's functions (e.g., Input, etc). Also, these project can be converted to have either OpenGL 1.1 or have software rendering.

# TODO
High Priority:
- [ ] Work on the code


Medium Priority:
- [ ] Optimize the inDot/Godot98 experience for all devices


Low Priority:
- [ ] Support beyond older Windows, such as MacOS, Linux, Dreamcast, etc.
- [ ] Make sure .pck extraction works on older Windows versions
