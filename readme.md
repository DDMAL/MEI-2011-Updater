Takes a single MEI file and converts it to the new camelCase tags. Also does a few other little updates along the way.

It compiles & runs on OSX & Linux.

## Compile

g++ -c -I/usr/include/libxml2 mei2011updater.cc

g++ -o mei2011updater -lxml2 mei2011updater.o

### Windows Instructions

Craig Sapp has generously provided a Makefile for compiling on Windows. You will need [MingW](http://www.mingw.org/) and [libxml2](http://xmlsoft.org/).

Further instructions are provided in the comments of the Makefile.
