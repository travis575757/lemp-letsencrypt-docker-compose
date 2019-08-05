# lemp-letsencrypt-docker-compose
A docker-compose webserver that actually provides ssl and a database.

Configuration:

For database structure and configuration use config/mysql/init/schema.sql

For letsencrypt container : https://hub.docker.com/r/linuxserver/letsencrypt

For mysql container : https://hub.docker.com/_/mysql

Bare minimum set up:

1. Set URL field in docker-compose under webserver.
2. Set root password and database name in docker-compose under mysql
3. make sure port 443 is opened on the machine be used on.
