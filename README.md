# fnlock-switch-tp-comp-usb-kb
Gnome Shell Extension - FnLock switch (LG Gram) - 

Why. There is an issue with LG Gram - FnLk doesn't work by pressing Fn+Esc in Linux. Manual toggling by writing 1|0 into `/sys/devices/platform/lg-laptop/fn_lock` is possible though


\
Fn is unlocked\
![screenshot00](https://github.com/goloshubov/tp-comp-keyboard-fnlk-switch/blob/master/about/screenshots/ss00.png)

Fn is locked (FnLk)\
![screenshot01](https://github.com/goloshubov/tp-comp-keyboard-fnlk-switch/blob/master/about/screenshots/ss01.png)

Notice that (Gnome) user should have write access to `/sys/devices/platform/lg-laptop/fn_lock`

You might add write access for your user doing:

```
sudo sudo chown your_user_name /sys/devices/platform/lg-laptop/fn_lock

```
