# Minimal development image for symfony
# Mount your project dir at /app
FROM composer:1.10

WORKDIR /app

RUN curl https://get.symfony.com/cli/installer | bash \
    && mv /root/.symfony/bin/symfony /usr/local/bin/symfony

CMD ["symfony", "server:start"]