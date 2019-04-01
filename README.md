# Compiling for lua on windows 10 x64

build `pcre2-8` project for configuration Release and platform x64

Run _x64 Native Tools Command Prompt for VS 2017_ and  install with luarocks pointing at the proper directories.

```luarocks install Lrexlib-PCRE2 PCRE2_DIR=H:\GitHub\pcre2-win-build\build-VS2017\x64\Release PCRE2_INCDIR=H:\GitHub\pcre2-win-build\include```

# Original readme
## pcre2-win-build

pcre2 Windows build with Visual Studio.

This version is pcre2-10.32.

See win-build-info for general information about the
win-build effort.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)
