FROM ubuntu:18.04
LABEL maintainer="ruyin_zh@126.com"
ENV REFRESHED_AT=2020-12-29

RUN apt-get update && apt-get install -y redis-server redis-tools

EXPOSE 6379
ENTRYPOINT [ "/usr/bin/redis-server" ]
CMD []