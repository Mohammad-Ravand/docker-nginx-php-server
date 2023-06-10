FROM php:8.0-fpm-alpine

WORKDIR /app

COPY . .


RUN addgroup -g 1000 laravel && adduser -G laravel -g laravel -s /bin/sh -D laravel

USER laravel 

# RUN chown -R laravel:laravel .