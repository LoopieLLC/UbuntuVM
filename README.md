# UbuntuVMImage
A Ubuntu 18.04.1 VM image for the dev team

It is important to make sure that the entire development team is working in the same environment to avoid conflicts.  
The selected environment is a Linux distribution called Ubuntu Xenail (16.04.4).

If you are working with OSX or Windows you will need to download VirtualBox via https://www.virtualbox.org/wiki/Downloads (select your operating system).

Next, you will want to download the Ubuntu 16.04 Xenial 64bit VID (https://www.osboxes.org/ubuntu/)

This will leave you with a .7z compressed file.  You need to unzip it using a 7z tool.  You may need to download this tool.  There are many tools and tutorials online.

Once you have done that you can follow this tutorial (https://blogs.oracle.com/oswald/importing-a-vdi-in-virtualbox) for importing the .vdi file into VirtualBox to create a new Ubuntu virtual machine.

When you get to step 3 of the tutorial pick the option to use an existing hard disk and browse for the .vdi file that you unziped and then click "create".

After you launch the virtual machine, a Ubuntu distribution will launch and you will be taken to a login screen.  You will be prompted for a password. 
pswd: osboxes.org
