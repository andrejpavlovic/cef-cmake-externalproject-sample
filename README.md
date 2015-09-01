# CEF CMake ExternalProject Sample

Example of how ExternalProject_Add can be used to load a [CEF3 Builds](https://cefbuilds.com/) as a dependency in our own cmake project.

## Caveats

The example only works on Windows and Mac, but similar modifications can be made to work on Linux.

## Build

  1. Clone repo
  2. Setup URL in [CMakeLists.txt](CMakeLists.txt#L147). (Find build URLs on [CEF3 Builds](https://cefbuilds.com/))
  3. `mkdir build && cd build`
  5. `cmake -G "Visual Studio 12" ..`
  6. `cmake --build .`  (CEF will be downloaded in this step)
