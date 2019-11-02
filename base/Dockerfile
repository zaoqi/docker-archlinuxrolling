FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm --needed base && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
