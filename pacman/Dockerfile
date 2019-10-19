FROM archlinux/base
RUN pacman -Syu --noconfirm && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*

FROM scratch
COPY --from=0 / /
ENV LANG=en_US.UTF-8
CMD ["/usr/bin/bash"]
