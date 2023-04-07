# Some notes on Amiga port

## configure

CC=m68k-amigaos-gcc CPPFLAGS="-mcrt=clib2" ./configure --host=amiga --enable-static --disable-largefile --disable-zlib --disable-syslog --disable-shadow --enable-bundled-libtom --disable-lastlog --disable-utmp --disable-utmpx --disable-wtmp --disable-wtmpx --disable-loginfunc --disable-pututline --disable-pututxline 
