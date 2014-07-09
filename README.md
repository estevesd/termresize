termresize
==========

When working on an embedded Linux box via serial port, it assumes that your Terminal window is 24 lines and 80 columns.
This script determines the real size of the window and updates 'stty' accordingly.

Installation :

    wget https://raw.githubusercontent.com/daff/termresize/master/termresize
    cp termresize /usr/local/bin/
    chmod +x /usr/local/bin/termresize

To launch at boot :

    echo "bash /usr/local/bin/termresize" >> ~/.bash

To launch at boot for all users :

    echo "bash /usr/local/bin/termresize" >> /etc/bash.bashrc

When the windows's size changes after boot :

    termresize

