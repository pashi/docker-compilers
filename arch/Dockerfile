FROM base/arch:latest
MAINTAINER Pasi Lammi <pasi.lammi@iki.fi>

RUN /usr/sbin/pacman-key --populate archlinux
RUN /usr/sbin/pacman-key --refresh-keys
RUN pacman -Syu --noconfirm
RUN pacman-db-upgrade

RUN pacman -S  autoconf automake binutils bison fakeroot file findutils flex gawk gcc gettext grep groff gzip libtool m4 make patch pkg-config sed sudo texinfo util-linux which --noconfirm
