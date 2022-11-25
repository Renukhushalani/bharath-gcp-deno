FROM centos:centos8

MAINTAINER Bharath Raj 

RUN yum -y upgrade \
    && yum install -y \
        initscripts \
        wget \
        libaio \
        telnet \
    && yum -y clean all
