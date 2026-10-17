# VMProtect3.5.1

VMProtect 3.5.1 full src.

存档备份用。

## Build entry points

The original [README](README) refers to `./build.sh` on POSIX and
`build.bat` on Windows. Neither script is included in this snapshot, so
those commands cannot be run directly from this checkout.

The Windows Visual Studio solution is [vmprotect.sln](vmprotect.sln), with
project files under [vcproj/](vcproj/). The solution is a starting point
for inspecting the build configuration; it does not replace the missing
build scripts or guarantee that all required dependencies are configured.
