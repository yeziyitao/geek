# hello world by asm @macos (brew install nasm)

bash-3.2# ll

total 24

-rw-r--r--  1 yezi  staff  119  4  8 23:06 Makefile

-rw-r--r--  1 yezi  staff   28  4  8 23:07 Readme.md

-rw-r--r--  1 yezi  staff  265  4  8 23:06 helloworld.asm

bash-3.2# make

nasm -f macho64 -o HelloWorld.o HelloWorld.asm

ld HelloWorld.o -o HelloWorld -macosx_version_min 10.13 -lSystem

bash-3.2# ./HelloWorld 

helloworld

bash-3.2#

