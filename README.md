## Blitz3D open source release, Chaduke's fork primarily for integration with LibSGD

### Building Blitz3D from source

You will need to install Microsoft Visual Studio 2026, and the CMake and Git utilities. 

You will also need to install the following optional MSVC components: "Desktop development with C++", "MFC and ATL support" and "ASP.NET and web development".

Then, from a DOS prompt:

``` shell
git clone https://github.com/blitz-research/blitz3d_soloud.git
cd blitz3d_soloud
cmake -S . -B cmake-build-release -A Win32 -G "Visual Studio 18 2026"
cmake --build cmake-build-release --config Release
```
Assuming all went well, the BLITZ3D_INSTALL directory will contain the final binaries, simply run Blitz3D.exe to get blitzing!
