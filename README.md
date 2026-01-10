## dwm - dynamic window manager - My build
![](DWM1.jpg)


This is my personal build of dwm (dynamic window manager). I built this for myself so I know exactly what is running on my computer at all times. By using this setup I’ve stripped away all the useless apps and background processes that come with standard desktops leaving only the tools I actually want/need


 ## How it works

I used the Suckless framework and manually added the features (patches) I wanted. It’s a mix of C code and shell scripts that I've tweaked to make everything work together.

* The Code: I took the raw C source code and applied patches for things like transparency, window gaps, and color support.

* The Logic: I added some small scripts to handle things like connecting to WiFi and other quality-of-life logic. It's just simple stuff to make sure the PC works exactly how I want it to without any extra junk.

* The Result: A system that uses almost zero RAM, works perfectly, and looks exactly how I want it to.



## Applied Patches

I’ve hand-patched this build to include only the essential features for my workflow:

*  [**colorbar**](https://dwm.suckless.org/patches/colorbar/) - Adds color to the status bar.
*  [**vanitygaps**](https://dwm.suckless.org/patches/vanitygaps/) - Inner and outer gaps for the modern look.
*  [**status2d**](https://dwm.suckless.org/patches/status2d/) / [**statuscmd**](https://dwm.suckless.org/patches/statuscmd/) - Allows for colored text and clickable buttons in the status bar.
*  [**alpha**](https://dwm.suckless.org/patches/alpha/) - Enables transparency for the bar and windows.
*  [**xrdb**](https://dwm.suckless.org/patches/xrdb/) - Allows for live color reloading without recompiling.
*  [**alwayscenter**](https://dwm.suckless.org/patches/alwayscenter/) - Floating windows always open in the center of the screen.
*  [**attachbottom**](https://dwm.suckless.org/patches/attachbottom/) - New windows are added to the bottom of the stack instead of the master.



