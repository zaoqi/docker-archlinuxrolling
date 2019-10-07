FROM archlinuxrolling/base
RUN pacman -Syu --noconfirm llvm clang lldb lld && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
