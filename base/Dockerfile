FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm base && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
