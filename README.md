# MSP430 Projects
Updated 2017-09-08

This repository will document development of MSP430 projects using `MSP430-GCC` and `mspdebug``.

This [document](http://www.phas.ubc.ca/~michal/phys319/tools_install-linux.pdf) has been very very helpful to get the workflow and tools setup in Linux:


The general workflow is to

$ cd examples/cblink
$ make
$ mspdebug rf2500

Then when in the debugger,

$ prog main.elf
CTRL+D



