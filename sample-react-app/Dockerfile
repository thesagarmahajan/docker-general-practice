FROM ubuntu
RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get install -y nodejs
COPY ./build /var/www/html
CMD apachectl -D FOREGROUND