# OpenSource-C-Arkanoid
C++ Arkanoid with open source code

Исходные тексты в стандарте C++11, являются кроссплатформенными.

Можно компилировать под "юниксы" на gcc (для запуска под "юникс" потребуется установленный опенсурс пакет ImageMagick, libao, libpthread, libsndfile; см Makefile).

https://www.xiph.org/ao/

http://www.mega-nerd.com/libsndfile/


Описание папок в архиве:
 
 Binaries(MinGW-W64.gcc) - ресурсы и бинарники откомпилированные в mingw-w64 (64-битный gcc для Windows)
 
 Binaries(MSVC++.Win32) - ресурсы и бинарники откомпилированные в Microsoft VC++ (VS2013) (Win32)
 
 Binaries.Linux - ресурсы и бинарники откомпилированные в g++ (Linux Mint 17 64-bit)
 
 Resource Sources - исходные картинки и PSD
 
 Source - исходные тексты на кроссплатформенном C++11

P.S.: "convert.exe" в папках с бинарниками - файл из пакета ImageMagick, нужен для работы с ресурсами