# Use the base PHP Apache image
FROM mcr.microsoft.com/devcontainers/php:0-8.2

# Install common development tools including git and sudo.
# 'sudo' is included for general utility, though permissions often work without it.
# 'apt-get update' fetches package lists, 'apt-get install -y' installs packages.
RUN apt-get update && apt-get install -y \
    git \
    sudo \
    default-mysql-client \
    && rm -rf /var/lib/apt/lists/* 

# Ensure the git executable has correct permissions.
# This addresses the "Permission denied" error for 'git'.
RUN chmod +x /usr/bin/git && chown root:root /usr/bin/git

# Install necessary PHP extensions for MySQL (mysqli, pdo, pdo_mysql)
# 'docker-php-ext-install' compiles and installs extensions.
# 'docker-php-ext-enable' explicitly enables some extensions.
# 'mysqlnd' is the native driver used by mysqli and pdo_mysql.
RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql 