# RoamPI
## Getting Started
1. Go to https://docs.flutter.dev/get-started/install, choose your operating system, and follow the instructions. This includes extracting flutter in an appropriate folder (such as C:\dev\flutter), updating environment variables to include flutter in path, and downloading Android Studio and appropriate sdks/tools.
2. Download VS Code and Flutter/Dart extension (optional).
3. Install Build Tools for VS (link on flutter install page), and be sure to include MSVC v143, C++ CMake tools for Windows, and Windows 11 SDK. This is for Windows app development.
4. Continuously run `flutter doctor` in terminal to make sure all requirements are satisfied (if command is unrecognized, env path was not set correctly in step 1).
5. Navigate to an appropriate folder for the `RoamPI` project and run `git clone https://github.com/mattsweet417/RoamPI.git`
6. To launch project in VS Code, run `code .` in terminal.
7. To run project in VS Code, first do `Ctrl/Command + Shift + P`, type in select device (if flutter option does not show, extension not properly installed) and choose emulator (see [article](https://www.geeksforgeeks.org/how-to-run-a-flutter-app-on-android-emulator/) if no emulator is shown), then run `flutter run` in terminal or press `Ctrl/Command + F5` in VS Code.