FROM centos:7
MAINTAINER ursbrchandra@gmail.com
RUN yum -y update
RUN yum -y install httpd
ADD code /var/www/html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]