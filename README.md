Docker-Host-Tools
=================

Some handy tools for managing Docker images and containers.


## Common tools

- `docker-rm-stopped` -
  Remove old stopped Docker containers, with optional `--dry-run` mode.

- `docker-rmi-repo` -
  Remove all Docker images belonging to specific repo name, with optional `--dry-run` mode.

- `docker-inspect-attr` -
  Inspect the attribute (e.g., IP address, pid) of a running Docker container.



## Private registry tools

- `DOCKER` (all uppercase) -
  Simple Docker CLI wrapper to "pull" public registry images from private registry.

- `docker-mirror` -
  Pull images from Docker Hub, and push them to private registry.



## Deprecated

- `boot2docker-alias` -
  Convenient alias for [boot2docker](http://boot2docker.io/) users.


