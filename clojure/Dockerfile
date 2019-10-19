FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm clojure && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
