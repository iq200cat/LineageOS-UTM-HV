# LINEAGEOS 22.1 UTM/QEMU ARM
## this project image maintener by 0xCAFEBABE as lineageOS builder

i just try to install this OS using UTM HV mode on iphone 14 pm 16.3.1 with hypervisor work on this ios version

HOW TO?
create vm with, at least 2GB RAM, 
first virtio disk = 13GB
second virtio disk = at least 2GB
enable UEFI boot
use AC97 sound card
use virtio pci gpu
insert the installer image as usb drive
boot it
perform android's factory reset
flash the android OTA zip
done

https://wiki.lineageos.org/libvirt-qemu#install-lineageos-to-the-virtual-machine
