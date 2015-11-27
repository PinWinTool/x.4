# Pinguino IDE Installation & Use Instructions

Pinguino was written in 2008 by Jean-Pierre Mandon and released under a GPL license.
Since its initial release there have been numerous bug fixes and improvements.
As of February 2010, the code was moved to Google Code where all the "users turned developers"
can access the same source tree.
Pinguino is constantly being updated with all the users' and developers' input.

This file is free documentation; you have unlimited permission to copy,
distribute and modify it.

Pinguino is an arduino like environment built in Python.
It is a complete package with compiler, assembler, linker and bootloader.
Pinguino is compatible with arduino/wiring language.

## Dependencies

### Linux
- libusb
- python 2.5
- wxpython 2.8

### Windows
- python 2.5
- wxpython 2.8

### Mac OS X 10.6 (Snow Leopard)
- python 2.6.1 (32 bit)
- wxpython 2.8 (32 bit)
- libusb 0.1.4
- pyusb 0.4.3

## Pinguino (8 bit) is based on open source software:

- compiler      SDCC                 http://sdcc.sourceforge.net/
- asm/linker    GPUTILS              http://gputils.sourceforge.net/
- bootloader    (v1,2) VASCO project http://vasco.gforge.enseeiht.fr/
- bootloader    (v3) Diolan          http://www.diolan.com/pic/
- bootloader    (v4) JAL Project     http://www.justanotherlanguage.org/
                and Alexander Enzmann's USB Framework
- IDE           Python               http://www.python.org/

## Pinguino (32 bit) is based on open source software:

- compiler    GCC       http://gcc.gnu.org/
- asm/linker  BINUTILS  http://www.gnu.org/
- C library   Newlib    http://sourceware.org/newlib/
- IDE         Python    http://www.python.org/

Contributions, bug reports and questions are welcome.
rblanchot@gmail.com
yeison.eng@gmail.com
