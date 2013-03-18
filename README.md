rootfs-shrink
=============

Chris Tyler, Seneca College

Script to take an SD card image (such as for a
Raspberry Pi) with an dos disklabel and two 
partitions (boot vfat and rootfs extX), and shrink
it so that the rootfs (2nd partition) is as short 
as possible plus a small free space allowance.

See comments at the top of the script for further
details.

