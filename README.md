README.md

# Corebell Engine  

**Corebell Engine** is a powerful and modular framework designed for 2D and 3D game creation. While its primary focus is on game development, its extensible design allows for creating additional tools, such as music and shader editors.  

⚠️ **This project is currently in development and not yet ready for public release. Stay tuned for updates!** ⚠️  

## **Table of Contents**  
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Folder Structure](#folder-structure)  
4. [Applications](#applications)  
5. [Libraries and Dependencies](#libraries-and-dependencies)  
6. [Build Instructions](#build-instructions)  
7. [Example Projects](#example-projects)  
8. [Contributing](#contributing)  
9. [License](#license)  

## **Introduction**  

The Corebell Engine aims to empower developers to create:  
- 2D games with efficient rendering and physics systems.  
- 3D games using advanced graphics and physics engines.  
- Tools and editors to enhance creativity and productivity (future updates).  

With a flexible architecture and Python scripting support, developers can rapidly prototype and extend the engine to suit their needs.  

## **Features**  
- **2D Rendering**: Sprite-based rendering, animations, and collision handling.  
- **3D Rendering**: Modern rendering techniques, including PBR, lighting, and shadow mapping.  
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.  
- **Python Integration**: Leverage Python for scripting and customization using `PyBind11`.  
- **Physics**: Integrated 2D and 3D physics systems using industry-standard libraries.  
- **Editor Support**: (Planned) Tools for creating and editing levels, shaders, and more.  

## **Folder Structure**  
```plaintext  
CorebellEngine/  
├── assets/               # Static files (icons, textures, sounds, etc.)  
├── docs/                 # Documentation and guides  
├── engine/               # Core engine source code  
│   ├── 2d/               # 2D engine modules (rendering, physics)  
│   ├── 3d/               # 3D engine modules (graphics, physics)  
│   ├── core/             # Core systems (event handling, resource management)  
│   ├── tools/            # Shared utilities (math, data structures)  
│   ├── audio/            # Audio subsystem  
│   └── scripting/        # Python scripting integration  
├── examples/             # Sample projects  
│   ├── 2d_game/  
│   ├── 3d_game/  
│   └── custom_tool/  
├── libs/                 # Third-party libraries (SDL2, OpenGL, etc.)  
├── shaders/              # Shader programs (GLSL or Vulkan-compatible)  
├── tools/                # Standalone tools (level editor, shader editor, etc.)  
├── tests/                # Unit and integration tests  
├── CMakeLists.txt        # Build configuration  
├── LICENSE               # License file (TBD)  
└── README.md             # This file

Applications

The Corebell Engine includes tools and applications to streamline game and tool development.

Current Applications (Planned Development)

1. Corebell Editor:

Visual level editor for building and organizing game scenes.

2. Shader Editor:

Create and test custom shaders in real-time.

3. Scripting Console:

Interactive Python console for debugging and testing
Libraries and Dependencies

Corebell Engine uses the following third-party libraries:

SDL2: Window creation, input management.

OpenGL: 2D/3D rendering pipeline.

Vulkan (Optional): Advanced 3D rendering support.

Box2D: 2D physics simulation.

Bullet Physics: 3D physics simulation.

PyBind11: Python integration.

Dear ImGui: GUI for tools and editors.

Additional dependencies will be added as development progresses.

Build Instructions

Prerequisites

1. A modern C++ compiler (C++17 or later).


2. CMake 3.15 or higher.


3. Python 3.9 or later (for scripting).


4. SDL2, OpenGL, and other dependencies installed.



Building the Engine

1. Clone the repository:

git clone https://github.com/corebel/CorebellEngine.git  
cd CorebellEngine


2. Configure the build system with CMake:

mkdir build && cd build  
cmake ..


3. Build the project:

cmake --build .




---

Example Projects

Check out the examples/ folder for starter projects:

1. 2D Game: A simple platformer showcasing sprites, animations, and physics.


2. 3D Game: A basic FPS demonstrating rendering, lighting, and collisions.




---

Contributing

Contributions are currently on hold while the engine is in development. Once ready, we will share detailed contribution guidelines in the CONTRIBUTING.md file.


---

License

Corebell Engine is currently proprietary and not yet licensed for public use. Licensing details will be provided upon release.
