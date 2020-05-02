FROM httpd:latest
CMD apt-get update && apt-get install -y ssh
RUN echo 'Apache con Docker y Ansible' > /var/www/index.html
<<<<<<< HEAD
EXPOSE 22 80
ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D, "FOREGROUND"]
=======
ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D, "FOREGROUND"]
EXPOSE 22 80
>>>>>>> 64710a01a9f31c59ec33b0f65bb064f08ca9d851
