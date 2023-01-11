# OpenSUSE MicroOS combustion

## Create USB

To create the USB use this code

```bash
mkfs.ext4 /dev/sdX
e2label /dev/sdX combustion
mount /dev/sdX /mnt
git clone https://github.com/SolidRhino/openSUSE-MicroOS-combustion.git
```
