#[Quickstart Guide: Compose and Rails](https://docs.docker.com/compose/rails/)
--------------------------------

file for Quickstart Guide

How to:

### Init

```sh
# build docker image
$ ./_docker_bin/build
# rails new
$ ./_docker_bin/new
# replace database.yml
$ mv database.yml config/database.yml
```

### Run

```sh
$ ./_docker_bin/up
```

### Update Gems

```sh
# rebuild your docker image
$ ./_docker_bin/build
```
