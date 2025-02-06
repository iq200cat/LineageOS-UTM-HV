# LINEAGEOS 22.1 UTM/QEMU ARM
## this project image maintener by 0xCAFEBABE as lineageOS builder

i just try to install this OS using UTM HV mode on iphone 14 pm 16.3.1 with hypervisor work on this ios version

# HOW TO?
# create vm with, at least 2GB RAM, 
1. first virtio disk = 13GB
2. second virtio disk = at least 2GB
3. enable UEFI boot
4. use AC97 sound card
5. use virtio pci gpu
6. insert the installer image as usb drive
7. boot it
8. perform android's factory reset
9. flash the android OTA zip
10. done

https://wiki.lineageos.org/libvirt-qemu#install-lineageos-to-the-virtual-machine
