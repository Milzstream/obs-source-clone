# Source Clone for OBS Studio

Plugin for OBS Studio to clone sources

Requires OBS Studio 33 or newer. The Windows installer uses `C:\ProgramData\obs-studio\plugins\source-clone`. Portable OBS: extract the Windows zip into the `plugins` folder beside `bin`.

# Build
1. In-tree build
    - Build OBS Studio: https://obsproject.com/wiki/Install-Instructions
    - Check out this repository to plugins/source-clone
    - Add `add_subdirectory(source-clone)` to plugins/CMakeLists.txt
    - Rebuild OBS Studio

1. Stand-alone build (Linux only)
    - Verify that you have package with development files for OBS
    - Check out this repository and run `cmake -S . -B build -DBUILD_OUT_OF_TREE=On && cmake --build build`

# Donations
https://www.paypal.me/exeldro
