Debian 8 DKMS Package for UAS Driver
====================================

The Linux kernel that comes delivered with Debian 8 does not have the
UAS (USB Attached SCSI) driver enabled.

I found extracting the driver code from the kernel source and creating
a DKMS package for it the easiest way to install the kernel module
properly.
