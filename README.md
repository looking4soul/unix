# unix

This is the source code of book *Advanced Programming in the UNIX Environment Second Edition*.

Directory apue.2e is download from http://apuebook.com/src.2e.tar.gz, which is in the offical website of the book.

## how to build

To build the source, edit the Make.defines.* file for your system and set
WKDIR to the pathname of the tree containing the source code.  

Then just run "make". 

### build single file

cd mycat

gcc mycat.c ../lib/error.o -I../include -o mycat