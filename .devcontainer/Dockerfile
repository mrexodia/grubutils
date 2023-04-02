FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu-18.04

RUN apt-get update && apt-get install -y \
  git \
  gcc-4.8 \
  gcc-4.8-multilib \
  nasm \
  p7zip-full \
  autoconf \
  automake \
  make \
  patch \
  binutils-dev \
  liblzma-dev \
  gcc-mingw-w64-i686 \
  && rm -rf /var/lib/apt/lists/*

RUN update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 1