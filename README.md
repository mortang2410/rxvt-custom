run 
```shell
cd rxvt-unicode
./configure \
    --prefix=/usr \
    --enable-256-color \
    --enable-combining \
    --enable-fading \
    --enable-font-styles \
    --enable-iso14755 \
    --enable-keepscrolling \
    --enable-lastlog \
    --enable-mousewheel \
    --enable-next-scroll \
    --enable-perl \
    --enable-pointer-blank \
    --enable-rxvt-scroll \
    --enable-selectionscrolling \
    --enable-slipwheeling \
    --enable-smart-resize \
    --enable-startup-notification \
    --enable-transparency \
    --enable-unicode3 \
    --enable-utmp \
    --enable-wide-glyphs \
    --enable-wtmp \
    --enable-xft \
    --enable-xim \
    --enable-xterm-scroll
make -j8
```

Then run your distro's favorite replacement of `make install`. For instance, run `sudo checkinstall` for Ubuntu/Debian.
