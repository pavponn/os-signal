# SIGSEGV Handler
SIGSEGV handler is a simple segmentation fault handler.
This is an educational project, aimed at understanding how to handle with segmentation fault.

## What does it do?
* Dumps values of general purpose registers, corresponding to the fall moment;
* Dumps memory near the address where the memory protection violation occurred


## Build
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```
Requires C++14 compiler

## Test
Tested manually on Linux 4.12.

## Copyright
Pavel Ponomarev, 2019 (pavponn@gmail.com)

MIT License.

