# kernup
Bash Script To Build Kernels With Debian

This code is to automate the process of building kernels on Debian based systems. It has been tested on Debian Sid, Kali Linux and Devaun. If you are on a virtual machine with no EFI, you may need to edit values pertaining to this in your .config or this code my fail. The following dependancies will also be needed to use this code:

rsync 
curl 
sudo 
make 
libncurses-dev 
fakeroot 
xz-utils 
build-essential 
flex 
bison 
bc 
libelf-dev 
libssl-dev 
dwarves

You may install them with the following:

sudo apt install rsync curl sudo make libncurses-dev fakeroot xz-utils build-essential flex bison bc libelf-dev libssl-dev dwarves

While this code has been throughly tested, we cannot shield anyone that has edited and created a bad .config file. For this reason, this code is consider as-is, with no warranty. 
