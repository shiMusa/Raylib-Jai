# Raylib-Jai
Raylib 4 bindings for Jai

This binding is created using the `Bindings_Generator` module of the compiler, plus a few minor tweaks and additions.

See `main.jai` for an example on how to use it in Jai.

`raylib.[dll/lib]`, `raylibdll.lib` (depending on your system) has to be placed next to the executable.

Tested on Windows 11 x86-64 so far.
If anyone has macOS or Linux, feel free to generate bindings for that system and add them to this repository. Just add the dynamic libraries and `raylib.h` to the folder and run `first.jai`. You might need to make some adjustments to the generated bindings (adding the constant `Color`s e.g. (`RAYWHITE` etc.)).