#
# Makefile
#

CIRCLEHOME = ../..

OBJS	= main.o kernel.o screentask.o primetask.o ledtask.o

LIBS	= $(CIRCLEHOME)/lib/usb/libusb.a \
	  $(CIRCLEHOME)/lib/input/libinput.a \
	  $(CIRCLEHOME)/lib/fs/libfs.a \
	  $(CIRCLEHOME)/lib/fs/fatfs/libfatfs.a \
	  $(CIRCLEHOME)/lib/sched/libsched.a \
	  $(CIRCLEHOME)/lib/libcircle.a \
	  $(CIRCLEHOME)/addon/SDCard/libsdcard.a \
	  $(CIRCLEHOME)/lib/pegasos/libpegasos.a

include ../Rules.mk

-include $(DEPS)
