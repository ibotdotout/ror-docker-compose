#[Quickstart Guide: Compose and Rails](https://docs.docker.com/compose/rails/)
--------------------------------

file for Quickstart Guide

How to:

### Init

```sh
# build docker image
$ ./bin/dbuild
# rails new
$ ./bin/dnew
# replace database.yml
$ mv database.yml config/database.yml
```

### Run

```sh
$ ./bin/dup
```

### Update Gems

```sh
# rebuild your docker image
$ ./bin/dbuild
```
