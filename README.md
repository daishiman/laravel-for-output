# initial-setting-laravel(docker đł)

<img src="https://user-images.githubusercontent.com/35098175/145682384-0f531ede-96e0-44c3-a35e-32494bd9af42.png" alt="docker-laravel">


## Introduction

Build a simple laravel development environment with docker-compose. Compatible with Windows(WSL2), macOS(M1) and Linux.



## ä˝żç¨ćšćł

**čŠłç´°č¨­ĺŽăŻ [wiki](https://github.com/daishiman/initial-setting-laravel/wiki) ĺç§**

1. Click [Use this template](https://github.com/daishiman/initial-setting-laravel)
2. Git clone & change directory
3. Execute the following command

```bash
$ make create-project # Install the latest Laravel project
$ make install-recommend-packages # Optional
```

http://localhost

## ĺč

- Read this [Makefile](https://github.com/daishiman/initial-setting-laravel/blob/main/Makefile).
- Read this [Wiki](https://github.com/daishiman/initial-setting-laravel/wiki).

## ăłăłăăć§é 

```bash
âââ mysql
âââ nginx
âââ php
```

### php ăłăłăă

- Base image
  - [php](https://hub.docker.com/_/php):8.1-fpm-bullseye
  - [composer](https://hub.docker.com/_/composer):2.2

### nginx ăłăłăă

- Base image
  - [nginx](https://hub.docker.com/_/nginx):1.22

### mysql ăłăłăă

- Base image
  - [mysql/mysql-server](https://hub.docker.com/r/mysql/mysql-server):8.0

### mailhog ăłăłăă

- Base image
  - [mailhog/mailhog](https://hub.docker.com/r/mailhog/mailhog)
