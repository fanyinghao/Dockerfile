FROM alpine:3.10

ENV OSSUTIL_VERSION 1.6.6

ADD http://gosspublic.alicdn.com/ossutil/${OSSUTIL_VERSION}/ossutil64 /usr/local/bin/ossutil

RUN chmod a+x /usr/local/bin/ossutil

ENTRYPOINT ["/usr/local/bin/ossutil"]