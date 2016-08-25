# Yuki FM
This is yet another file manager being made with Lua Player Plus. As of this writing, it is currently suited for normal use. More features will be pushed to the repo

# What is working
* Built In updater
* Basic file browsing
* File Unzipping and copy/pasting
* Theme engine
* CIA Installing
* 3DSX Launching
* Lua script loading
* Viewing extdata

# Features that will come soon
* News:S (Notifiation) Browsing
* proper Built-In updater

# Contributing
I can only work on this 3 days a week due to me being in school. so If you want to contribute, feel free to make a pull request ^^
##Build instructions
The building is made possible through a `make` script, meaning you need to have `make` installed and in your path. If you already use devkitArm then you are good to go

Just run `make` (or `make all`/`make build`) to get your binaries in the build directory

`build 3ds`, `build 3dsx` and `build cia` are also available in case not all binaries need to be built.

You can also use `make clean` to remove all built files.
## Nightlies
Nightlies are available at [the official automatic Nightly build page](https://hikiruka.github.io/Yuki-FM/build/) and build whenever changes get pushed to the `master` branch


## Credits
* Rinnegatamante for Lua Player Plus, [lpp-3ds](https://github.com/Rinnegatamante/lpp-3ds) and ORGANIZE3D as it uses some (mostly) of his code
* ihavemac for YAFM As it utulizes some of his code
* astronautlevel2 for the proper updating screen as used in [Star Updater](https://github.com/astronautlevel2/StarUpdater)
* Wolvan for the nightlies
