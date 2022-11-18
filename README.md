# cunnywm - Cunny Window Manager 
cunnywm is an extremely fast, small, and dynamic window manager for X.

### Installation:
```
    meson build
    ninja -C build
    sudo ninja install
```

### Testing: 
```
    Xephyr :1 -ac -screen 854x480&
    startx -- /usr/bin/Xephyr :1
``` 
