FROM httpd:latest
CMD apt-get update && apt-get install -y ssh
COPY index.html /var/www/html/
EXPOSE 22 80
ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D, "FOREGROUND"]
