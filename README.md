Dockerized REDIS for Drupal
-----------------------

[![Build Status](https://travis-ci.org/drupal-docker/redis.svg?branch=master)](https://travis-ci.org/drupal-docker/redis)
[![Docker Pulls](https://img.shields.io/docker/pulls/drupaldocker/redis.svg?maxAge=2592000)](https://hub.docker.com/r/drupaldocker/redis)

Version | Tags | Dockerfile
--- | --- | --- | ---
3.2 | `latest`, `3.2`, `3` | [Dockerfile](https://github.com/drupal-docker/redis/blob/master/3.2/Dockerfile)
3.0 | `3.0` | [Dockerfile](https://github.com/drupal-docker/redis/blob/master/3.0/Dockerfile)
2.8 | `2.8`, `2` | [Dockerfile](https://github.com/drupal-docker/redis/blob/master/2.8/Dockerfile)

# Quickstart:

````
docker run -d --name redis drupaldocker/redis
````

# Environmental variables

No variables

# Description

> Redis is an open-source, networked, in-memory, key-value data store with optional durability. It is written in ANSI C. The development of Redis has been sponsored by Pivotal since May 2013; before that, it was sponsored by VMware. According to the monthly ranking by DB-Engines.com, Redis is the most popular key-value store. The name Redis means REmote DIctionary Server.

> source: [redis](https://hub.docker.com/_/redis/)

# Status

Proof of concept

# Contributing

1. Fork the repo
1. Create your feature branch
1. Commit your changes
1. Push to the branch
1. Create new Pull Request
1. Wait for result of automate tests

# Credits
drupaldocker/redis was built on the top of official [redis images](https://hub.docker.com/r/_/redis/).
