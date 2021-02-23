This repository contains the starting code for OSI Lab 3 on device drivers.
YOu will need make, flex and bison to build the driver.

You might need to do something like
sudo apt-get install make
sudo apt-get install flex
sudo apt-get install bison
sudo apt-get install git

git clone https://github/focussed/osi_lab3
cd osi_lab3/drivers
make

This will give a nothing.ko file
You can install this into the kernel by entering

sudo insmod nothing.ko

You can see the kernel loaded by entering

lsmod | grep nothing



