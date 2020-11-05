
FROM centos:7

RUN yum -y update && \
    yum -y install httpd php

COPY . /var/www/html

CMD [ "httpd", "-DFOREGROUND" ]