# Використовуємо офіційний образ WordPress як базу
FROM wordpress:6.6.0

# Встановлюємо необхідні інструменти, такі як WP-CLI (опціонально)
RUN apt-get update && apt-get install -y less vim \
    && curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar \
    && chmod +x wp-cli.phar \
    && mv wp-cli.phar /usr/local/bin/wp
