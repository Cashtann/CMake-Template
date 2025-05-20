# CMake Project Template (Basic)

### Golden quote - "It works on my machine"

My custom simple CMake Template (rather for Linux because of .sh scripts). DRY, so this template is for me (and others if they want) to use.
This template is fairly simple and very basic, as I mentioned I use it when I want to make fast and easly a new project.
I use `CMake` and `Make` to generate and build project.
Clone this repo:
```
gh repo clone Cashtann/CMake-Template
```

**Make scripts executable if you want**
```
chmod +x setupCMake.sh compile.sh run.sh
```


### Scripts:
**Setup CMake**

This creates CMake files in `build` directory.
 ```
 ./setupCmake.sh
```
This script is just bash `cmake -B build` (if you want to make it on Windows, you may need to use `cmake -B build -G "MinGW Makefiles"`).

**Build project**

Compiles project. Output files (executable and libs) should be inside `./bin` folder.
 ```
 ./compile.sh
```

**Run project**

Compiles project and runs the executable file. 
File location may differ depending on Build mode *(Debug/Release)* -> set in the CMakeLists.txt file.
 ```
 ./run.sh
```
This script is the same as `compile.sh` but also has `cd bin/Linux/Debug && ./run && cd ..`.

