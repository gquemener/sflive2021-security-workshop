FROM php:8.0-cli-alpine

RUN docker-php-ext-install pdo_mysql

COPY --from=composer /usr/bin/composer /usr/bin/composer

CMD ["php", "-v"]
