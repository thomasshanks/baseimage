FROM phusion/baseimage:0.9.17
MAINTAINER Thomas Shanks <tshanks@avinetworks.com>

RUN apt-get update
RUN apt-get install -y curl git vim wget tcpdump
RUN apt-get autoremove -y
RUN apt-get clean
RUN rm -rf /var/lib/apt/lists
