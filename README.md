#Racing

##Description
Racing simulator that involves networking (TCP), strategies (AI), console drawing (curses), threading, testing (catch).

##Build intructions
###Windows:
- Install <a href="https://sourceforge.net/projects/mingw-w64/">MinGW-w64</a>
- Build <a href="https://github.com/Bill-Gray/PDCurses">pdcurses</a> library and then add it to MinGW, or just download already prepaired <a href="https://drive.google.com/file/d/0BwinoxM7BwFqNWlOUXQxYWRyb2c/view?usp=sharing">MinGW</a>
- Use `mingw32-make` to build

###Linux:
- Install `ncurses` e.g. `sudo apt-get install libncurses5-dev`
- Install `gpm` e.g. `sudo apt-get install libgpm-dev`
- Use `make` to build