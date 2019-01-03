# How to use the 'make4061' program.

1. On the command line, type 'make' to utilize the Makefile and create the 'make4061' file.

  $ make

2. If the program compiles without any errors, type 'ls' to check whether 'make4061' has been created. If 'make4061' exist, this means that the program is ready to use.

  $ ls

  $ ./make4061

    This will run the program and show the proper outputs.

3. After checking ./make4061 command works, we can try a command to compile only a specific Makefile.

  $ ./make4061 -f filename

  If filename is not mentioned or specified, it will detect the Makefile automatically.

4. Next, check whether the program can build a specific target in the Makefile.

  $ ./make4061 specificTarget

  This will make 'make4061' to build only the target mentioned.

5. Check whether usage information is shown with the command,

  $ ./make4061 -h

  This will print out the usage info.
