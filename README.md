# My suckless utilities configuration based on [NiceMicro](https://www.youtube.com/c/NiceMicroLinux)

## How to install?
Just run *makepkg -sif --clean* on dw,/ and on st/ folders

## How to update the configs?
All configuration must be done in the config.h file. After that, you must use the command *makepkg -if --clean* 

## How to patch?
For patching, you have to add the .diff file inside the source variable on PKGBUILD and the respective sha256sum to the sha256sums variable