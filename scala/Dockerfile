FROM archlinuxrolling/base
RUN pacman -Syu --noconfirm scala sbt && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
