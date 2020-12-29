FROM ubuntu:18.04
LABEL "maintainer"="ruyin_zh@126.com"
ENV REFRESHED_AT 2020-12-29
RUN apt-get update && apt-get -y -q install nginx
RUN mkdir -p /var/www/html
# 将下载的本地文件的nginx配置
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80