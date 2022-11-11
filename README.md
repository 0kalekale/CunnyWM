# CunnyWM - Cunny Window Manager (part of sysk)

CunnyWM is an extremely fast, small, and dynamic window manager for X.


## Requirements

In order to build CunnyWM you need the Xlib header files.


## Installation
```
    meson build
    ninja -C build
    sudo ninja install
```

## Running CunnyWM

Add the following line to your .xinitrc to start dwm using startx:

```
    exec cunnywm
```

## Configuration

SOON^TM (for now edit src/config.h and recompile)

### Note

cunnywm is a fork of dwm.
