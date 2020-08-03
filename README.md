# Docker Web Stack

Consists of:
- Elasticsearch
- Kibana
- Mailhog
- MongoDB
- Mongo Express
- MySQL
- PHPMyAdmin
- Portainer
- Redis
- Redis Commander

## Prerequisites
You will need the following software installed.
- Docker
- Docker Compose

## Setup

1. Clone this project.
```shell script
$ git clone git@github.com:mattsbanner/php-docker-config.git
```

2. Create your environment file by copying _.env.example_ to _.env_.
```shell script
$ cd php-docker-config
$ cp .env.example .env
```

3. Go through the _.env_ file and replace the variable placeholders (e.g _%%PLACEHOLDER_EXAMPLE%%_) with your desired configuration.

4. Use Docker Compose to bring up the project. This may take a while to clone the images on the first occasion.
```shell script
$ docker-compose up -d
```

**That's it!**
