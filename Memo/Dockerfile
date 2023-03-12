FROM ubuntu:18.04
RUN apt-get update -y
RUN apt-get install apache2 -y

WORKDIR /var/www/html

EXPOSE 8081

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]