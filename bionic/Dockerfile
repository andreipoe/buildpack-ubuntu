FROM ubuntu:bionic
LABEL maintainer "Andrei Poenaru <docker@simd.stream>"

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y \
        autoconf \
        autotools-dev \
        bison \
        build-essential \
        cmake \
        curl \
        gettext \
        git \
        libcurl4-openssl-dev \
        libevent-dev \
        libncursesw5-dev \
        libreadline6-dev \
        libssl-dev \
        musl-tools \
        ncurses-dev \
        pandoc \
        pkg-config \
        wget \
        xz-utils \
        zlib1g-dev && \
    apt-get clean

