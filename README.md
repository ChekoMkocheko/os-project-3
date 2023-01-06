This program impliments a scaled down version of malloc. 
To use this version of malloc, you need to preload it 
the libc environment. See Makefile debugging example:
gdb --args env LD_PRELOAD=./my-malloc.so ls -l

