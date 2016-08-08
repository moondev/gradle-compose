FROM ubuntu:trusty

MAINTAINER cmoon@kenzan.com

RUN apt-get update
RUN apt-get install -y nginx


EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]