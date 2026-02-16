# SPDX-FileCopyrightText: 2025 ETH Zurich and University of Bologna
#
# SPDX-License-Identifier: Apache-2.0
FROM ubuntu:22.04

ARG TARGETPLATFORM
ENV DEBIAN_FRONTEND=noninteractive

ENV TZ=Etc/UTC
ENV LANG=C.UTF-8
ENV LC_ALL=C.UTF-8

# Change the working directory
WORKDIR /app/build

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y  \
        autoconf \
        automake \
        autotools-dev \
        bc \
        bison \
        build-essential \
        ccache \
        clang-format \
        curl \
        device-tree-compiler \
        doxygen \
        flex \
        g++ \
        gawk \
        gcc \
        gcc-x86-64-linux-gnu \
        gdb-multiarch \
        git-lfs \
        gperf \
        gtkwave \
        ibglib2.0-dev \
        libftdi-dev \
        libftdi1 \
        libmpc-dev \
        libmpfr-dev \
        libpixman-1-dev \
        libsdl2-dev \
        libsdl2-ttf-dev \
        libsndfile1-dev \
        libtool \
        libusb-1.0-0-dev \
        nano \
        ninja-build \
        patchutils \
        pkg-config \
        protobuf-compiler \
        python-is-python3 \
        python3 \
        python3-dev \
        python3-pip \
        python3.10-distutils \
        python3.10-venv \
        rsync \
        scons \
        ssh \
        sudo \
        telnet \
        texinfo \
        usbutils \
        wget \
        zlib1g-dev \
        zsh && \
    rm -rf /var/lib/apt/lists/*

