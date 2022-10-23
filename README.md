# rt-n14u-scripts
Assortment of scripts I made to easily install Entware and/or other cool stuff on ASUS RT-N14U. Router is running stock ASUS firmware `3.0.0.4.380_8285`. These scripts allow me to:
- version control my router configs using git;
- control my local network `hosts` file on the router remotely;
- update scripts to a new version over-the-air by sending UDP packets.

# Installation
1. Prepare USB drive with ext2/ext3.
2. Clone this repo to USB drive.
3. Connect USB to router.
4. Connect to router using telnet.
5. Check for USB volumes with `blkid`. In my case it was `/dev/sda1`.
6. Mount USB volume to `/tmp/opt`.
7. Run `install` script from cloned folder.
