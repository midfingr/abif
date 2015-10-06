================================
Arch Base Installation Framework
================================
A generic *offline* installer for Arch-based ISOs. Feel free to use it for your distribution.

================================
Features
================================
+ Seamless BIOS and UEFI Support
+ Configured to use translation files
+ Easy customisation / basic configuration
+ Supports LVM and btrfs (including special mounting and sub-volume creation)
+ Create multiple users
+ Built-in error detection

================================
Basic Assumptions
================================
+ dialog *must* be installed
+ Boot menus assume Grub, Syslinux, systemd-boot and rEFInd are installed
+ Default partitioning tools are parted, cfdisk, cgdisk, fdisk, and gdisk
+ You will need to add your own post-configuration code for DMs, and specific files
