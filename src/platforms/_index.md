# Bevy on Different Platforms

Bevy trivially works out-of-the-box on the major desktop operating systems:
Linux, macOS, Windows. No special configuration is required.

See the following pages for specific tips/advice when developing for the
desktop platforms:
 - [Linux](./linux.md)
 - [macOS](./macos.md)
 - [Windows](./windows.md)

Bevy aims to also make it easy to target other platforms, such as web browsers
(via WebAssembly), mobile (Android and iOS), and game consoles. Your Bevy
code can be the same for all platforms, with differences only in the build
process and environment setup.

However, that vision is not fully met yet. Currently, support for non-desktop
platforms is limited, and requires more complex configuration:

 - [Web Browsers](./wasm.md): It is possible to make a web game, with some caveats.
 - Mobile: support is minimal and broken. It will build, but may or may not run.
   Expect to immediately encounter major issues.
 - Game consoles: support is still completely non-existent yet.
 
If you are interested in these other platforms and you'd like to help improve
Bevy's cross-platform support, your contributions would be greatly welcomed!
