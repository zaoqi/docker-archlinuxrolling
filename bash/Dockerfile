FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm bash && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
