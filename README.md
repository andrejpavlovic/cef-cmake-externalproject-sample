# CEF CMake ExternalProject Sample

Example of how ExternalProject_Add can be used to load a [CEF3 Build](https://cefbuilds.com/) as a dependency in our own cmake project.

## Caveats

The example only works on Windows, but similar modifications can be made to work on Linux and Mac.

## Build

  1. Clone repo
  2. mkdir build
  3. cd build
  4. cmake -G "Visual Studio 12" ..
  5. cmake --build .

NOTE: You may want to adjust the url to [CEF3 Build](https://cefbuilds.com/) in [CMakeLists.txt](CMakeLists.txt).
