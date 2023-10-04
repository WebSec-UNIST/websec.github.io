FROM i386/debian:buster
MAINTAINER Seongil Wi <seongil.wi@unist.ac.kr> 

RUN mkdir -p /workdir
WORKDIR /workdir

RUN apt-get -y update && apt-get -y upgrade


RUN apt-get install -y sudo
RUN apt-get install -y vim
RUN apt-get install -y gdb
RUN apt-get install -y binutils
RUN apt-get install -y wget
RUN apt-get install -y ssh-client
RUN apt-get install -y llvm
RUN apt-get install -y netcat
RUN apt-get install -y gcc
RUN apt-get install -y python3

