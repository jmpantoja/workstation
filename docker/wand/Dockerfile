FROM composer:latest

ENV COMPOSER_HOME /root

COPY composer.json /root/composer.json

#RUN composer global require planb/utils:dev-develop
#RUN composer global require planb/wand:dev-develop

RUN composer global update

#COPY composer.json /composer.json

COPY wand-entrypoint.sh /wand-entrypoint.sh

