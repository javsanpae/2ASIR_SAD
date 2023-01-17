# v1.0
FROM ubuntu/squid:latest

RUN apt-get update
RUN apt-get install -y apache2-utils

WORKDIR /etc/squid/
# COPY ./prohibidas.txt .
# COPY ./squid.conf .
RUN /usr/sbin/squid reload

# d run -dti --name=squid -p 3128:3128 -v `pwd`/conf/:/etc/squid/ javsanpae/sad-squidproxy:1.0