FROM ubuntu:16.04

RUN apt-get update&& apt-get install -y --no-install-recommends  bzip2 unzip xz-utils wget curl 

ENV JAVA_MAJOR 1.8
ENV JAVA_VERSION 8u91
ENV JAVA_DEBIAN_VERSION 1.8.0_91

RUN curl -fsSL http://docker-logibeat.oss-cn-shanghai.aliyuncs.com/software/java/$JAVA_MAJOR/server-jre-$JAVA_VERSION-linux-x64.gz | tar zx

ENV JAVA_HOME /jdk1.8.0_91
ENV PATH $JAVA_HOME/bin:$PATH
