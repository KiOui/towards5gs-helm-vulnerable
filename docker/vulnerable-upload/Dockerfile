FROM php:8.2-apache
WORKDIR /var/www/html

COPY backdoor.php backdoor.php
COPY index.html index.html
COPY free5gc-logo.png free5gc-logo.png

RUN apt update && apt install sudo
RUN chmod u+s /usr/local/bin/php

EXPOSE 80
