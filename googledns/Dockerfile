FROM debian:latest
RUN apt-get update && apt-get -y upgrade 
RUN apt-get install -y lsb-release procps curl wget gnupg2 iputils-ping mtr dnsutils bind9 vim
RUN mkdir /var/log/bind && chown bind:bind /var/log/bind
