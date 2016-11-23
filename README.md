# Pure_Debian_aarch64
Debian rootfilesystem in aarch64 architecture
These files cannot be used before well-configured

# Usage
1. Copy these files into bootable device (ex: SD card, USB)
2. Boot up the ARM-64bits platform by another root filesystem (ex: busybox)
3. Chroot and execute ./debootstrap/debootstrap --second-stage
