all: enumfiles

enumfiles: enumfiles.c
	x86_64-w64-mingw32-gcc -o enumfiles.o -c enumfiles.c -Wno-write-strings 
	
	#-Os -s -Qn -nostdlib -Wl,-s,--exclude-all-symbols
