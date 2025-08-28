# Lua

This repository contains a Visual Studio 2022 solution with 4 projects:

- Lua interpreter
- Lua dynamic link library (for interpreter)
- Lua compiler
- Lua setup for windows

The DLL (lua.dll) is a dependency of the interpreter project (lua.exe). The compiler (luac.exe) is a standalone project. All three are dependencies of the setup project (setup.exe and luasetup.msi).

The source code (see src folder) is shared (in part or in whole) by the compiler, interpreter and DLL. 

All source code Copyright (c) 1994-2025 Lua.org, PUC-Rio

