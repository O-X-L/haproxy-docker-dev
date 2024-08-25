# HAProxy - Development Branch Dockerized

## Build

`docker build --no-cache --build-arg HAPROXY_BRANCH=<YOUR-TARGET-BRANCH> -t haproxy-dev .`

## Notes

The `Dockerfile` is sourced from [haproxytech/haproxy-docker-alpine](https://github.com/haproxytech/haproxy-docker-alpine) and modified to compile the provided dev version instead of a release.

The source code is loaded from GitHub.

You could also define a specific commit as `HAPROXY_BRANCH`.

The dataplane-API was stripped from the image.
