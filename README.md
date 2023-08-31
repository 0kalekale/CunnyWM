# NOTE: DEPRICATED. see sysk/bin/desktop/syskwm for my new window manager
tho i will still use cunnywm until syskwm is fully usable. 
this code base got messy while i was working on my personal branch 
so instead of building on top of dwm i want to start over
with wayland this time
the master/main whatever branch is still very much usable and barely has any 
frontend changes from vannila dwm. 

note: there is still a shitty monkey patch that i need to get rid of, closing browser popups kills the whole browser 

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
