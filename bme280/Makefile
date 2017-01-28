BINARY = bme280
OBJS = main.o
LDSCRIPT = ../stm32f103.ld
SCRIPT_DIR = ..

default: $(BINARY).bin
	$(Q)$(PREFIX)-size $(BINARY).elf

include ../Makefile.include

