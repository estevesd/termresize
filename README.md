termresize
==========

When working on a Linux box via serial port, it assumes that your Terminal window is 24 lines and 80 columns.
This script determines the real size of the window and updates 'stty' accordingly.
Useful when working on Raspberry Pi, Beaglebone or any small ARM development boards.

Runs on Debian Wheezy. Not tested in other distributions.

Installation :

    wget https://raw.githubusercontent.com/estevesd/termresize/master/termresize
    mv termresize /usr/local/bin/termresize
    chmod +x /usr/local/bin/termresize

To launch at boot :

    echo "bash /usr/local/bin/termresize" >> ~/.bash

To launch at boot for all users :

    echo "bash /usr/local/bin/termresize" >> /etc/bash.bashrc

When the windows's size changes after boot :

    termresize

