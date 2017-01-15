FROM alpine:3.5
MAINTAINER Benoît Vidis <contact@benoitvidis.com>

RUN  apk update \
  && apk add --no-cache --virtual zm \
    nginx \
    php7-fpm \
    php7-pdo \
    php7-pdo_mysql \
    zoneminder
    
