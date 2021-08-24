# About this Repository
This repository containts several scripts that can be helpful when setting up alpine linux.

## bspwm-setup
This script can be helpful when setting up bspwm for alpine linux. Additionally this script can install polybar and picom as a compositor.

## setup-glx

### Warning!

Installing `mesa-dri-gallium` which is included in the setup `setup-glx` script, will break keyboard input in bspwm. To circumvent this issue comment out `picom` in the `bspwmrc` file like this `#picom --experimental-backends -b` 

The `setup-glx` script will install basic GLX utilities that are needed when running games like Mindustry on alpine linux.


