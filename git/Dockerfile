FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm git && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
