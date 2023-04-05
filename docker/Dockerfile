FROM php:8.2-apache
WORKDIR /var/www/html

COPY vulnerable-upload.php vulnerable-upload.php
COPY index.html index.html

RUN apt update && apt install sudo
RUN chmod u+s /usr/local/bin/php

EXPOSE 80
