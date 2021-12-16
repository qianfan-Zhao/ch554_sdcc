TARGET = bbb_lcd

# based on the datesheet 18.4 section:
# Vcc >= 4.4V, fsys_max = 24MHz
# Vcc >= 3.3 && Vcc < 4.4, fsys_max = 16MHz
# Vcc < 3.3, fsys_max = 12MHz
FREQ_SYS=16000000

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
