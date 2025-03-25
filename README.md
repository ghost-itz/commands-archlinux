## Some usefull command to use in Arch Linux

Update the whole system

    sudo pacman -Syuu

Remove cached packages that are not currently installed

    sudo pacman -Sc

Remove all package from cache

    sudo pacman -Scc

Remove unused packages

    sudo pacman -Qtdq

    sudo pacman -Rns $(pacman -Qtdq)

Clean cache in $HOME directory

    rm -rf ~/.cache/*

List packages installed from AUR

    pacman -Qm

Search packages

    pacman -Ss