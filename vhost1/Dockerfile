FROM php:7.4-apache

# Install additional PHP extensions and dependencies if needed
# For example, if using MySQL, you might need to install the mysqli extension
# RUN docker-php-ext-install mysqli

# Copy your PHP application files to the container
COPY . /var/www/html/

# Set the working directory
WORKDIR /var/www/html/