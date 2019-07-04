# Install Debian 9 on a ThinkPad X220

1. Download latest Debian file for creating a USB bootable drive, file: [amd64-netist.iso](https://www.debian.org/distrib/netinst)

2. Convert the .iso file to a bootable (in Mac OS): follow this [guideline](https://blog.tinned-software.net/create-bootable-usb-stick-from-iso-in-mac-os-x/)

3. Put your USB stick and Reboot the x220 (Assume the bios can set for the boot sequence). The GUI screen should start.

4. Installation issue: 

* prepare a spare machine where you can download the missing firmware on another USB (search online for the specific missing files) e.g [iwlwifi-6000g2b-5.ucode](https://github.com/OpenELEC/iwlwifi-firmware/blob/master/firmware/iwlwifi-6000g2b-5.ucode) and [iwlwifi-6000g2b-6.ucode](https://github.com/cernekee/linux-firmware/blob/master/iwlwifi-6000g2b-6.ucode)   
* `apt-get install sudo` (Add username into sudo list: https://www.reddit.com/r/linuxquestions/comments/6a0apo/debian_gnome_username_is_not_in_the_sudoers_file/)

# Additional software that I have installed 

* nodejs -> for coding
* git -> for code management
* atom -> for code editing
* Thunderbird -> for email
* ownCloud-client -> for cloud storage
* zotero -> for referencing system (flatpak run org.zotero.Zotero)
* powertop -> for improving battery level
* acpi -> check battery and charging quality 
* ibus-cangjie- > Chinese input 

Useful linux commands

```
//root
su-
```

```
//root
Su root
```

```
//check diskspace
df -H
```
