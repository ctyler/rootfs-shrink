rootfs-shrink
=============

Chris Tyler, Seneca College

Script to take an SD card image (such as for a Raspberry Pi) with a dos 
disklabel and two partitions (boot vfat and rootfs extX), and shrink it 
so that the rootfs (2nd partition) is as short as possible plus a small
free space allowance.  

See comments at the top of the script for further details.

This script is licensed under the GPL v2, or at the user's discretion, 
any later version.

The web page and git repository for this code is accessible at the
[Github Repo](https://github.com/ctyler/rootfs-shrink)

