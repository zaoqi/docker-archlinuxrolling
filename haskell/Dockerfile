FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm stack ghc cabal-install && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
