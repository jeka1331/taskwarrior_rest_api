FROM archlinux:base-devel
RUN pacman -Sy 
RUN yes | pacman -S archlinux-keyring
RUN yes | pacman -S task
RUN ln -sf /usr/share/zoneinfo/Asia/Almaty /etc/localtime
