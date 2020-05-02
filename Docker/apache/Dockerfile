FROM ubuntu:xenial
RUN apt-get update && apt-get install -y apache2 && apt-get install -y ssh
COPY index.html /var/www/html/
EXPOSE 22 80
RUN /etc/init.d/apache2 start
RUN /etc/init.d/ssh start
CMD ["/usr/sbin/apache2","-D", "FOREGROUND"]
