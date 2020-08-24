FROM ubuntu

ENV OBSUTIL_VERSION 5.2.5

ADD https://obs-community.obs.cn-north-1.myhuaweicloud.com/obsutil/current/obsutil_linux_amd64.tar.gz /

RUN tar -xzf /obsutil_linux_amd64.tar.gz

RUN mv /obsutil_linux_amd64_${OBSUTIL_VERSION}/obsutil /usr/local/bin/obsutil

RUN chmod a+x /usr/local/bin/obsutil