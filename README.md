# imperial
Imperial plays the Imperial March using the beep utility

This is an install package for Arch Linux and can be installed with the official method for installing unsupported packages, which is exhaustively described in the [AUR](https://wiki.archlinux.org/index.php/AUR) article.

Here is how, in a nutshell:
```shell
wget https://raw.githubusercontent.com/itay-grudev/imperial/arch/PKGBUILD
makepkg -s
pacman -U imperial-*.pkg.tar.xz
```

Startup Music
-------------
The Imperial March can be played during an early stage of system startup. To enable that feature, just run:
```
systemctl enable imperial
```

Copyright
---------
Itay Grudev 2015 <itay@grudev.com>
