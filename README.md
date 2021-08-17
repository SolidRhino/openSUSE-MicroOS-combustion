# OpenSUSE MicroOS combustion
---

## Create USB

To create the USB use this code
```
mkfs.ext4 /dev/sdY
e2label /dev/sdY combustion
mount /dev/sdY /mnt
git clone https://github.com/SolidRhino/openSUSE-MicroOS-combustion.git
```