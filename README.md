# HAProxy - Development Branch Dockerized

## Build

`docker build --no-cache --build-arg HAPROXY_BRANCH=<YOUR-TARGET-BRANCH> -t haproxy-dev .`

## Notes

The source code is loaded from GitHub.

You could also define a specific commit as `HAPROXY_BRANCH`.

The dataplane-API was stripped from the image.
