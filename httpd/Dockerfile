FROM centos:6.7

MAINTAINER Pablo Álamo González <palamgonz@gmail.com>

RUN yum install -y httpd

ADD index.html /var/www/html/

EXPOSE 80
CMD httpd -DFOREGROUND
