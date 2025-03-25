## Some usefull command to use in ArchLinux
## Alguns comandos úteis para se usar no ArchLinux

Update the whole system (Atualização de todo o sistema)

    sudo pacman -Syu

Remove cached packages that are not currently installed
(Remova pacotes (chache) que não estão instalados)

    sudo pacman -Sc

Remove all package from cache (Remover todos os pacotes do cache)

    sudo pacman -Scc

List unused packages (listar os pacotes não utilizados)

    sudo pacman -Qtdq
 
Remove unused packages (Remover pacotes não utilizados)

    sudo pacman -Rns $(pacman -Qtdq)

Clean cache in $HOME directory (Remover cache que está no diretório %HOME)

    rm -rf ~/.cache/*

List packages installed from AUR (Lista dos pacotes que estão no AUR)

    pacman -Qm

Search packages (Procurar por pacotes)

    pacman -Ss