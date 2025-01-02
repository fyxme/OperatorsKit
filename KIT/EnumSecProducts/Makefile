all: enumsecproducts

enumsecproducts: enumsecproducts.c
	x86_64-w64-mingw32-gcc -o enumsecproducts.o -c enumsecproducts.c -Wno-write-strings 
	
	#-Os -s -Qn -nostdlib -Wl,-s,--exclude-all-symbols
