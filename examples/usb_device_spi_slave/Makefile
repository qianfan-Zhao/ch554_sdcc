TARGET = usb_device_spi_slave

# Adjust the XRAM location and size to leave space for the USB DMA buffers
XRAM_SIZE = 0x0300
XRAM_LOC = 0x0100

EXTRA_FLAGS = --opt-code-speed

C_FILES = \
	main.c \
	../../include/debug.c \
	../../include/spi.c

pre-flash:


include ../Makefile.include
