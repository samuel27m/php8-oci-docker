# php8-oci-docker
Docker-compose with PHP 8 &amp; OCI Extensions, Apache 2.4, Mailcatcher

## Apache
**Version:** 2.4.38

## PHP
**Version:** 8.0.0

**Extensions enabled:** OCI & MySQL
#### If you need more PHP extensions, change the `php-apache/Dockerfile` file and restart the containers

# Mailcatcher
Included in case there is any emailing capabilities to test. See https://mailcatcher.me/ for information on how it works.


## Quick Start

#### Clone the repository:
`git clone https://github.com/samuel27m/php8-oci-docker`

#### Start the environment:
`docker-compose up -d`

#### Open your browser and go to:
`http://localhost:3333`

#### That's it 🎉

## Programs required

- Docker Desktop
- WSL2 
- **Enable WSL2 integration within Docker Desktop**
