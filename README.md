# Jekyll Twitter Bootstrap Static

## Overview

This repo contains a static site based on Twitter Bootstrap for use as a base
to create a Twitter Bootstrap-based Jekyll theme.

This repo will be used as a basis for the [Jekyll Twitter Bootstrap theme](https://github.com/KCarlile/jekyll-twitter-bootstrap).

GitHub repo: <https://github.com/KCarlile/jekyll-twitter-bootstrap-static>

## Depdendencies

- [Twitter Bootstrap 5.3](https://getbootstrap.com/docs/5.3/)
- [Docker >=4.15](https://www.docker.com/)
  - Docker configuration is provided for easy local development and testing,
    but you can use any hosting configuration that supports HTML.
- Bash *nix Shell
  - The `.server` and `setup-etc-hosts` files are written for Bash in *nix
    (Mac OS X, specifically) are helpful for Docker setup, but not required.

## Local Environment

- `Dockerfile`
  - Defines container with Apache 2.x
- `docker-compose.yml`
  - Launches the container
- `server`
  - Launches the Docker container at
    <http://jekyll-twitter-bootstrap-static.local/>
- `setup-etc-hosts`
  - Adds the proper entry to /etc/hosts, but must be run as root
    (`$ sudo ./setup-etc-hosts`)

## Author

Kenny Carlile

- GitHub account: [KCarlile](https://github.com/KCarlile)
- Website: [KCarlile.com](https://www.kcarlile.com/)
