# rp2040-geek-80-built

Insert the USB stick into computer, while holding the boot button
down.

The device will show up as a disk on your computer.

Copy the file picosim.uf2 into the USB disk.

Now, pull the device and plug it back in.  It should boot and display "waiting for console"
On linux, the console is /dev/ttyASC0 (maybe)

Then put your SD card into a programming device.  So, then copy the 3 three directories to the
SD card.  

Now, when the console is connected, there is a list of things, you need to assign 
disk 0 to cpm22 or cpm3-1

Then just say G and it will boot cpm.

