# CMake Project Template (Basic)
My custom simple CMake Template (rather for Linux because of .sh scripts). I'm lazy, so this template is for me (and others if they want) to download.
This template is fairly simple and very basic, as I mentioned I use it when I want to fast and easly make new project.
Clone this repo:
```
gh repo clone Cashtann/CMake-Template
```

**First of all, you may need to make those bash scripts executable, so in the project directory paste in these commands:**
```
chmod +x setupCMake.sh compile.sh run.sh
```


### Commands to use in project directory (bash scripts):
**CreateCMake files**

This creates CMake files in `build` directory.
 ```
 ./setupCmake.sh
```
**Build (compile) project**

Creates all necessary files, also in `build` directory.
 ```
 ./compile.sh
```
**Run project**

Another evidence that I'm lazy, guess what it does.
 ```
 ./run.sh
```
