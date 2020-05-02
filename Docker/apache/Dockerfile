FROM httpd:latest
CMD apt-get update && apt-get install -y ssh
EXPOSE 22 80
RUN echo 'Apache con Docker y Ansible' > /var/www/index.html
ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D, "FOREGROUND"]

