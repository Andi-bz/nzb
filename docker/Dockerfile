FROM nimmis/apache-php7
MAINTAINER cytec <iamcytec@googlemail.com>

RUN apt-get update && \
  apt-get install -y php7.0-xml


RUN a2enmod rewrite

EXPOSE 80
EXPOSE 443
