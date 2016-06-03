FROM ubuntu:16.04

RUN apt-get update&& apt-get install -y --no-install-recommends  bzip2 unzip xz-utils wget curl 

ENV JAVA_MAJOR 1.8
ENV JAVA_VERSION 8u91
ENV JAVA_DEBIAN_VERSION 1.8.0_91

RUN curl -fsSL http://docker-logibeat.oss-cn-shanghai.aliyuncs.com/software/java/$JAVA_MAJOR/jre-$JAVA_VERSION-linux-x64.gz > /jre-linux-x64.gz
RUN tar zxf /jre-linux-x64.gz
RUN rm -rf /jre-linux-x64.gz

ENV JAVA_HOME /jre1.8.0_91
ENV PATH $JAVA_HOME/bin:$PATH
