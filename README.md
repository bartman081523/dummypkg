usage:
dummypkg -S foo version    installs a dummy pkg with pkgver=version, a file that resembles the package name and version in /etc/dummy (uses sudo for pacman)
dummypkg -R foo       checks if foo has been installed by dummypkg and removes it with pacman
dummypkg -l              lists all packages and package versions of all packages installed by dummypkg

temporary building is done in ~/.dummypkg-tmp/


imported from Themaister http://themaister.net/blog https://bbs.archlinux.org/viewtopic.php?id=61001
