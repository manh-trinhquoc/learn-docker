# php-fpm
FROM php:fpm-alpine

RUN docker-php-ext-install mysqli pdo pdo_mysql
#RUN docker-php-ext-enable mysqli
# RUN apt-get update \
#     docker-php-ext-configure pdo_mysql --with-pdo-mysql=mysqlnd \
#     && docker-php-ext-configure mysqli --with-mysqli=mysqlnd \
#     && docker-php-ext-install pdo_mysql

CMD ["php-fpm"]

EXPOSE 9000