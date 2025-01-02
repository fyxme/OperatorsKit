all: enumdrives

enumdrives: enumdrives.c
	x86_64-w64-mingw32-gcc -o enumdrives.o -c enumdrives.c -Wno-write-strings 
	
	#-Os -s -Qn -nostdlib -Wl,-s,--exclude-all-symbols
