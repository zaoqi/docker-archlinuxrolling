FROM archlinuxrolling/base
RUN pacman -Syu --noconfirm racket-minimal && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
