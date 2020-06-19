This is mesa driver version 20.0.7 for ubuntu/debian/mint/popOS..

To install on fresh distro, go to the folder say libdrm-i386 and just run the command:

$ sudo dpkg -i *

An error will appear due to the lack of installed dependencies ..

To solve, type:

$ sudo apt --fix-broken install

And then again:

$ sudo dpkg -i *
