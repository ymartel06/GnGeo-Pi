GnGeo-Pi
==============

General Usage
-------------

GnGeo-Pi is a portable NeoGeo emulator optimized for Raspberry Pi (TM)

This emulator is tested with the RetroPie distribution (based on Raspian).

Currently, there is no official release, but you can download the source and put in /home/pi/RetroPie/emulators/gngeo-0.85/.


```shell
pushd "/home/pi/RetroPie/emulators/gngeo-0.85"
chmod +x configure
./configure --host=arm-linux --target=arm-linux --disable-i386asm --prefix="/home/pi/RetroPie/emulators/gngeo-0.85/installdir"
make
make install
popd
mv /home/pi/RetroPie/emulators/gngeo-0.85/installdir/bin/arm-linux-gngeo /home/pi/RetroPie/emulators/gngeo-0.85/installdir/bin/gngeo
mv /home/pi/RetroPie/emulators/gngeo-0.85/installdir/share/man/man1/arm-linux-gngeo.1 /home/pi/RetroPie/emulators/gngeo-0.85/installdir/share/man/man1/gngeo.1
```

Wiki
----

The wiki will open soon. Stay tuned.

Thanks
------

Many thanks to Mathieu Peponas, the original author of GnGeo.
