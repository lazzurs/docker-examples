FROM centos:6

MAINTAINER Rob Lazzurs <rob@lazzurs.org>

RUN yum install -y centos-release-scl

RUN yum install -y httpd24

RUN yum install -y php54

EXPOSE 80

ENTRYPOINT ["/opt/rh/httpd24/root/usr/sbin/apachectl", "-D", "FOREGROUND"]
