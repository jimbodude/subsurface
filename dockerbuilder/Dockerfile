FROM debian:stretch

WORKDIR /subsurface-src

RUN apt-get update
RUN apt-get install -y --no-install-recommends \
    git g++ make autoconf automake libtool cmake pkg-config \
	libxml2-dev libxslt1-dev libzip-dev libsqlite3-dev \
	libusb-1.0-0-dev libssl-dev \
	qt5-default qt5-qmake qtchooser qttools5-dev-tools libqt5svg5-dev \
	libqt5webkit5-dev libqt5qml5 libqt5quick5 \
	qtscript5-dev libssh2-1-dev libcurl4-openssl-dev qttools5-dev \
	qtconnectivity5-dev qtlocation5-dev qtpositioning5-dev \
	libcrypto++-dev libssl-dev

RUN apt-get install -y libgit2-dev ca-certificates
RUN apt-get clean
