# Caddy + bunny.net DNS

Docker image of Caddy built with `github.com/caddy-dns/bunny` via `xcaddy`.

## Build locally
docker build -t caddy-bunny:local .

## Run example
docker run --rm -p 80:80 -p 443:443 caddy-bunny:local caddy version
