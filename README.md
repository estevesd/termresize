termresize
==========

Resizing Terminal according to window size

Installation :

    wget https://raw.githubusercontent.com/daff/termresize/master/termresize
    cp termresize /usr/local/bin/
    chmod +x /usr/local/bin/termresize

To launch at boot :

    echo "bash /usr/local/bin/termresize" >> ~/.bash

To launch at boot for all users :

    echo "bash /usr/local/bin/termresize" >> /etc/bash.bashrc
