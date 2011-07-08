Takes a single MEI file and converts it to the new camelCase tags. Also does a few other little updates along the way.

It compiles & runs on OSX & Linux.

== Compile ==
g++ -c -I/usr/include/libxml2 meiconverter.cc
g++ -o meiconverter -lxml2 meiconverter.o

