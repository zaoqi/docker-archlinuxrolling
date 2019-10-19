FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm gcc && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
