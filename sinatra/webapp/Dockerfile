FROM ubuntu:18.04
LABEL "maintainer"="ruyin_zh@126.com"
ENV "REFRESHED_AT"="2020-12-29"

RUN apt-get update && apt-get install -y install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis

RUN mkdir -p /opt/webapp

EXPOSE 4567 

CMD [ "/opt/webapp/bin/webapp" ]