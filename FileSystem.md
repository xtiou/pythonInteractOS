## FHS Linux Standard Directory Tree
### DIRECTORY	PURPOSE
* /	Primary directory of the entire filesystem hierarchy
* /bin	Essential executable programs that must be available in single user mode
* /boot	Files needed to boot the system, such as the kernel, initrd or initramfs images, and boot configuration files and bootloader programs
* /dev	Device Nodes, used to interact with hardware and software devices
* /etc	System-wide configuration files
* /home	User home directories, including personal settings, files, etc.
* /lib	Libraries required by executable binaries in /bin and /sbin
* /lib64	64-bit libraries required by executable binaries in /bin and /sbin, for systems which can run both 32-bit and 64-bit programs
* /media	Mount points for removable media such as CDs, DVDs, USB sticks, etc.
* /mnt	Temporarily mounted filesystems
* /opt	Optional application software packages
* /proc	Virtual pseudo-filesystem giving information about the system and processes running on it. Can be used to alter system parameters.
* /run	Run-time variable data, containing information describing the system since it was booted. Replaces the older /var/run
* /sys	Virtual pseudo-filesystem giving information about the system and processes running on it. Can be used to alter system parameters. Similar to a device tree and is part of the Unified Device Model.
* /root	Home directory for the root user
* /sbin	Essential system binaries
* /srv	Site-specific data served up by the system. Seldom used.
* /tmp	Temporary files; on many distributions lost across a reboot and may be a ramdisk in memory.
* /usr	Multi-user applications, utilities and data; theoretically read-only.
* /var	Variable data that changes during system operation
