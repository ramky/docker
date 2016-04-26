FROM ubuntu:14.04
MAINTAINER Ram Iyer

ENV DEBIAN_FRONTEND=noninteractive

# Install base packages
RUN apt-get update
RUN apt-get install -y \
  build-essential \
  curl \
  git-core \
  libreadline-dev \
  libssl-dev \
  ubuntu-dev-tools \
  unzip \
  vim \
  wget \
  libpq-dev \
  libsqlite3-dev \
  zlib1g-dev


# Configure git
RUN git config --global color.ui true
RUN git config --global user.name "Ram Iyer"
RUN git config --global user.email "ramky.iyer@gmail.com"

