# Docker Based PHP Development Environment
**This project is a WIP. There is currently no stable functionality.**

> A full PHP development environment run within Docker. Includes NGINX, PHP 5.6, 7.0, 7.1, 7.2, 7.3 & 7.4, MySQL with a replication instance, PHPMyAdmin, MongoDB, Mongo Express, Redis, Redis Commander, Mailhog and Portainer to monitor the whole shebang.

## Prerequisites
You will need the following software installed.
- Docker
- Docker Compose

## Setup

1. Clone this project, better yet, [fork it](https://github.com/mattsbanner/php-docker-config/fork) and save your changes.
```shell script
$ git clone git@github.com:mattsbanner/php-docker-config.git
```

2. Create your environment file by copying _.env.example_ to _.env_.
```shell script
$ cd php-docker-config
$ cp .env.example .env
```

3. Go through the _.env_ file and replace the placeholders (e.g _%%PLACEHOLDER_EXAMPLE%%_) / port numbers with your desired configuration.

4. Use Docker Compose to bring up the project. This may take a while to clone the images on the first occasion.
```shell script
$ docker-compose up -d
```

**That's it!**