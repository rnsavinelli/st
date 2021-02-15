# rnsavinelli's build of st - simple terminal

This fork of [Simple Terminal (st)](https://st.suckless.org/) has my personal configurations, some patches and modifications.

## Patches

+ [Alpha](https://st.suckless.org/patches/alpha/)
+ [Scrollback](https://st.suckless.org/patches/scrollback/)
+ [Newterm](https://st.suckless.org/patches/newterm/)
+ [Clipboard](https://st.suckless.org/patches/clipboard/)

## Key Bindings

+ **Scrollback** one line at a time with `Shift+Up` and `Shift+Down`. Alternatively, since mouse scroll support is enabled, you can use `Shift+MouseWheel`.
+ **Copy text** from the terminal with `Ctrl+Shift+c`, **paste text** to the terminal with `Ctrl+Shift-v`.
+ **Zoom in** with `Ctrl+Shift+Add`, **Zoom out** with `Ctrl+Shift+Subtract`. Use `Ctrl-Shift-Home` to go back to the default setting.
+ Open up a **new terminal window** in the same working directory with `Ctrl+Shift+Enter`.

## Dependencies

`make`, `libX11` and `libXft` are required, but you probably have all of this installed already.

It uses Ubuntu Mono as the default font, so you'll need to have `ttf-ubuntu-font-family` installed in order for the text to be displayed properly.

For Alpha to work (the transparency patch), you'll need an X composite manager (e.g. compton, xcompmgr).

## Installation
```
git clone https://github.com/rnsavinelli/st
cd st
sudo make clean install
```

## Original project
st (simple terminal) original source code and information can be found here:

Website: [https://st.suckless.org/](https://st.suckless.org/)

Repository: [https://git.suckless.org/st/](https://git.suckless.org/st/)

