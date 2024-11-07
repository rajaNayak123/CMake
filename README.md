# What is CMake 🧐
  CMake is a tool that helps manage the build process of software projects. 
  It’s used with C and C++ programs to generate the necessary files to compile and link a program on different platforms. 
  CMake simplifies creating makefiles (for Linux) or project files (for Visual Studio on Windows) by writing a simple configuration file instead of creating them manually for each platform.
  ## Why Use CMake?
  - Cross-platform: It can generate build files for Windows, macOS, and Linux.
  - Easier management: Instead of writing specific makefiles for each environment, you only need to write one CMake configuration file.

 # How to install CMake (Using Homebrew)
  ## Homebrew
  Homebrew is a package manager for macOS and Linux that makes it easy to install, update, and manage software from the command line.
   Homebrew handles all these steps for you, resolving dependencies automatically and keeping everything organized.
   Run the Homebrew Installation Command:
  -     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  Verify Installation:
  -     brew --version
 Open Terminal.
Install CMake by running:
-     brew install cmake
Verify Installation by checking the version:
-     cmake --version
