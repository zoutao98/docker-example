FROM debian:11-slim

RUN mkdir /usr/local/jvm

ADD jdk-8u202-linux-x64.tar.gz /usr/local/jvm

ENV JAVA_HOME /usr/local/jvm/jdk1.8.0_202
ENV JRE_HOME /usr/local/jvm/jdk1.8.0_202/jre
ENV PATH $JAVA_HOME/bin:$PATH

WORKDIR /home
CMD [ "bash" ]