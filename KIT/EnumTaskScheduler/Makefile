all: enumtaskscheduler 

enumtaskscheduler: enumtaskscheduler.c
	x86_64-w64-mingw32-gcc -o enumtaskscheduler.o -c enumtaskscheduler.c -Wno-write-strings 

	#-Os -s -Qn -nostdlib -Wl,-s,--exclude-all-symbols
