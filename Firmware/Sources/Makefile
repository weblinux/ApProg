all:
	avr-gcc -mmcu=atmega8 -g -Os -c *.c -std=c99
	avr-gcc -g -mmcu=atmega8 -o flash.elf *.o
	avr-objcopy -j .text -j .data -O ihex flash.elf flash.hex
clean:
	rm *.o *.elf *.hex -f
