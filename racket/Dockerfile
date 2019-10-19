FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm racket && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
