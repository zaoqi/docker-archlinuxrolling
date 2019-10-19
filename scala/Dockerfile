FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm scala sbt && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
