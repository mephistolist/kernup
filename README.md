# kernup
Bash Script To Build Kernels With Debian

This code is to automate the process of building kernels on Debian based systems. It will grab the source of the latest stable kernel from kernel.org and build it with the .config of kernel currently running. This has been tested on Debian Sid, Kali Linux and Devaun. If you are on a virtual machine with no EFI, you may need to edit values pertaining to this in your .config or this code my fail. The following dependancies will also be needed to use this code:

rsync<br> 
curl<br> 
sudo<br> 
make<br> 
libncurses-dev<br> 
fakeroot<br> 
xz-utils<br> 
build-essential<br> 
flex<br> 
bison<br> 
bc<br> 
libelf-dev<br> 
libssl-dev<br> 
dwarves<br>

You may install them with the following:

sudo apt install rsync curl sudo make libncurses-dev fakeroot xz-utils build-essential flex bison bc libelf-dev libssl-dev dwarves

While this code has been throughly tested, we cannot shield anyone that has edited and created a bad .config file. For this reason, this code is consider as-is, with no warranty. That being said, you will need to edit your .config file before running this code for its changes to be applied. 
