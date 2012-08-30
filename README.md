# ArchLinuxARM makepkg on Ubuntu


### install packman

    wget http://projects.archlinux.org/pacman.git/snapshot/pacman-4.0.3.tar.gz
    tar xzf pacman-4.0.3.tar.gz
    cd pacman-4.0.3
    ./configure --disable-doc
    make
    sudo make install


### build package

    cd packagedir
    makepkg --config ../makepkg-arm.conf

