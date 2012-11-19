Virtual File System
=================

Virtual File System (VFS) is developed in C, with all basic File and Directory operations.

How to Run?
-----------

1) Extract the bundle and go to /build directory where you should find a makefile.

2) Type make in the shell and hit enter, it will create the executable in /bin directory.

3) Run the executable by giving it as input, a file containing commands to be executed.

    Example: ./vfsdriver ../test/interactive_input.txt

      interactive_input.txt is already available in /test directory with few commands. You can run and test the VFS using similar scripts.

Features
--------

Implemented all file operations like add, list, move, update, copy, remove, export, search.

All directory operations like make, list, delete and move are also implemented.

Data structures used are nAry Tree, Binary Search Tree and Hashtable.