FROM archlinuxrolling/base
FROM archlinux/base
RUN pacman -Syu --noconfirm --asdeps gzip pacman sed systemd && pacman -Syu --noconfirm base && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
