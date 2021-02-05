FROM ubuntu:20.04

RUN apt update && apt install -y rsyslog rsyslog-elasticsearch curl jq

COPY ./rsyslog.conf /etc/

ENTRYPOINT ["rsyslogd", "-n"]