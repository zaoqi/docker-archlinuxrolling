FROM archlinuxrolling/pacman
FROM archlinux/base
RUN pacman -Syu --noconfirm --asdeps gzip pacman sed systemd && pacman -Syu --noconfirm base && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*

FROM scratch
COPY --from=1 / /
ENV LANG=en_US.UTF-8
CMD ["/usr/bin/bash"]
