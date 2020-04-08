all:
	nasm -f macho64 -o HelloWorld.o HelloWorld.asm
	ld HelloWorld.o -o HelloWorld -macosx_version_min 10.13 -lSystem
