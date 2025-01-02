all: enumsysmon

enumsysmon: enumsysmon.c
	x86_64-w64-mingw32-gcc -o enumsysmon.o -c enumsysmon.c -Wno-write-strings 
	
	#-Os -s -Qn -nostdlib -Wl,-s,--exclude-all-symbols
