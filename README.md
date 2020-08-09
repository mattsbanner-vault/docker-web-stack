# Docker Web Stack

> A pre-defined Docker stack for running common services alongside your NGINX / Apache and PHP stack.

This Docker stack consists of.
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

**Please create an [issue](https://github.com/mattsbanner/docker-web-stack/issues/new) or [pull request](https://github.com/mattsbanner/docker-web-stack/compare) if there are any additional services you wish to be added.**

## Prerequisites
You will need the following software.
- Docker
- Docker Compose

## Setup

1. Clone this project.
```shell script
$ git clone git@github.com:mattsbanner/docker-web-stack.git
```

2. Create your environment file by copying _.env.example_ to _.env_.
```shell script
$ cd docker-web-stack
$ cp .env.example .env
```

3. Go through the _.env_ file and set the variables you wish to change.

4. Use Docker Compose to bring up the project. This may take a while to clone the images on the first occasion.
```shell script
$ docker-compose up -d
```
