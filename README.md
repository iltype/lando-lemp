# Lando Lemp Configuration

Lando is an extremely flexible local development environment that is based on Docker. If your system can run Docker, then you can run Lando regardless if you are on a Mac, Windows, or Linux machine. The beauty of Lando is that most of the Docker configuration is handled for you through prebuilt "recipes", which greatly simplifies the setup process.

This repository contains the Lando configuration file (.lando.yml) that I use for my WordPress projects along with the php.conf and default.conf(vhost) file that it references.

**Recipe Lemp**

- Nginx
- MariaDB
- Php
- VHost

**Tools**

- PhpMyAdmin
- Mailhog

## Install

---

1. Download and install [Docker desktop](https://www.docker.com/products/docker-desktop/)
2. Download and install [lando](https://github.com/lando/lando/releases)

## Usage

---

1. Start Docker Desktop
2. lando start
