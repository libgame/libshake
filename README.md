SNDO
====

[![Build Status](https://travis-ci.org/ssbx/sndo.svg?branch=master)](https://travis-ci.org/ssbx/sndo)
[![Appveyor Build Status](https://ci.appveyor.com/api/projects/status/github/ssbx/sndo?branch=master&svg=true)](https://ci.appveyor.com/project/ssbx/sndo)

Thin wrapper around the PortAudio library (http://www.portaudio.com/).

Build
-----
First init Git submodules:
```sh
git submodule init
git submodule update
```

SNDO is build with CMake for all platforms.

You can also use the fake configure script provided to set it up on unix:
```sh
$ ./configure
$ cd build && make all
```
