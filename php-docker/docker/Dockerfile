FROM php:8.0.2-fpm

RUN apt-get update && \
    apt-get install -y \
    curl \
    git \
    unzip \
    vim \
    zip && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* /var/cache/apt/archives/*

WORKDIR /var/www
