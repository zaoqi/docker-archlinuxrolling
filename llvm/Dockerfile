FROM archlinuxrolling/pacman
RUN pacman -Syu --noconfirm llvm clang lldb lld && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
