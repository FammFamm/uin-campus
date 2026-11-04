
# Partie A
## ii. Relevez les versions

**Résultat dans le terminal**
**g++** = g++ (Ubuntu 14.2.0-4ubuntu2~24.04.1) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

**clang++** = Ubuntu clang version 18.1.3 (1ubuntu1)
Target: x86_64-pc-linux-gnu
Thread model: posix
InstalledDir: /usr/bin

**cmake** = cmake version 3.28.3

CMake suite maintained and supported by Kitware (kitware.com/cmake).

**ninja** = 1.11.1

**gdb** = GNU gdb (Ubuntu 15.1-1ubuntu1~24.04.1) 15.1
Copyright (C) 2024 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

**git** 
git version 2.43.0 

**Conclusion Versions des outils**
- **g++** : Ubuntu 14.2.0
- **clang++** : Ubuntu clang version 18.1.3
- **CMake** : version 3.28.3
- **Ninja** : 1.11.1
- **gdb** : GNU gdb 15.1
- **git** : version 2.43.0

#
## Commandes du projet
- Configurer : `cmake --preset debug`
- Construire : `cmake --build --preset debug`
- Exécuter : `./build/debug/uin-campus`
- Formater : `find src include app -name "*.cpp" -o -name "*.h" | xargs clang-format -i`
- Analyser : `clang-tidy app/main.cpp src/version.cpp -p build/debug`