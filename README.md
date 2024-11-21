# Computer graphics in Game development course

This repository provides a template for labs in the Computer Graphics in Game Development course.

## Requirements

Before you start, make sure you have the following installed:

- Version control: [Git](https://git-scm.com/)
- C++ compiler: **MSVC**, Clang, GCC (C++17 compatible)
- Build System: [CMake](https://cmake.org/download/)
- IDE: [Visual Studio Community](https://visualstudio.microsoft.com/downloads/)
- DirectX Tools: [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/)

## Building the Solution
To clone this repository with all submodules, use the following command:

`git clone --recursive` 

Alternatively, if you've already cloned the repository, initialize the submodules with:

`git submodule update --init --recursive`

Next, navigate to the project folder and execute these commands to build:

```sh
mkdir Build
cd Build
cmake .. -A x64
```

## External Libraries and Assets

This project utilizes several third-party tools and data:

- [STB](https://github.com/nothings/stb) by Sean Barrett (Public Domain)
- [Linalg.h](https://github.com/sgorsten/linalg) by Sterling Orsten (The Unlicense)
- [Tinyobjloader](https://github.com/syoyo/tinyobjloader) by Syoyo Fujita (MIT License)
- [Cxxopts](https://github.com/jarro2783/cxxopts) by jarro2783 (MIT License)
- [Cornell Box models](https://casual-effects.com/g3d/data10/index.html#) by Morgan McGuire (CC BY 3.0 License)
- [Cube model](https://casual-effects.com/g3d/data10/index.html#) by Morgan McGuire (CC BY 3.0 License)
- [Teapot model](https://casual-effects.com/g3d/data10/common/model/teapot/teapot.zip) by Martin Newell (CC0 License)
- [Dabrovic Sponza model](https://casual-effects.com/g3d/data10/index.html#) by Marko Dabrovic (CC BY-NC License)

