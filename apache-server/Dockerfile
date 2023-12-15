FROM ubuntu
RUN apt-get update
RUN apt-get install -y apache2
COPY ./index.html /var/www/html
# Docker container needs atleast one foreground process
CMD apachectl -D FOREGROUND
