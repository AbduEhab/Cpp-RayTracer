# Overview

This is a Ray-Tracer which is extremly similar to the one I wrote in Java. Just wanted to make sure I can re-write any java code into cpp. I'll keep working on this project for a while.

Fully supports Windows (full UI and stuff) - Linux works in `Legacy mode` which would output the rendered image onto the terminal, macOS was not tested.

## Requirements (for compiling)
- [CMake](https://cmake.org/)
- [Vulkan SDK](https://vulkan.lunarg.com/sdk/home#windows)
- x64 Compiler (DOES NOT WORK WITH x86 COMPILERS!!!)

## Getting Started
Once you've cloned the repo, setup cmake with `cmake -S . -B build`. If you're using CMake with VS Code, the binaries should be automatically copied in to the bin folder (no mater the build config). 
Visual Studio (not VS Code) will Compile and link perfectly but will fail to copy the binary which would give you a "Build failed. do you want to start anyway?" message. You can ignore this message and launch anyway.

### 3rd party libaries
- [Walnut](https://github.com/TheCherno/Walnut)
- [stb_image_write](https://github.com/nothings/stb/blob/master/stb_image_write.h)
- [L2DFileDialog](https://github.com/Limeoats/L2DFileDialog)

### Demo Renders
![Demo 1](https://github.com/AbduEhab/Cpp-RayTracer/blob/main/bin/Main_Test_Scene.png)
