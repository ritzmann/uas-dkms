#
# Makefile for the USB Mass Storage device drivers.
#
# 15 Aug 2000, Christoph Hellwig <hch@infradead.org>
# Rewritten to use lists instead of if-statements.
#

CONFIG_USB_UAS=m

ccflags-y := -Idrivers/scsi

obj-m		+= uas.o
obj-m		+= usb-storage.o

usb-storage-y := scsiglue.o protocol.o transport.o usb.o
usb-storage-y += initializers.o sierra_ms.o option_ms.o
usb-storage-y += usual-tables.o
# usb-storage-y += debug.o

