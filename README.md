# Build-recorder

The purpose of this project is
to fully record the interactions
between assets (files and tools)
when a software artifact is being built (compiled).

## License

The code is licensed under
GNU Lesser General Public License v2.1 or later
(`LGPL-2.1-or-later`).


## Prerequisites

* Linux Kernel Version 5.3 (needed for PTRACE_GET_SYSCALL_INFO and more...)
* GNU Autotools 
    * sudo apt-get install autotools-dev
* Libssl
    * sudo apt-get install libssl-dev

## Compilation
We excecute the following commands:

`aclocal`

`autoreconf`

`automake --add-missing`

`autoreconf`

`./configure`

`make`
