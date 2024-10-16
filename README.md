## git clone

## Create the required directory

```shell
mkdir -p npm-data letsencrypt ~/Data/mariadb ~/Data/meilisearch ~/Data/redis
```

## Creating a shared_network in Docker Network

```shell
docker network create shared_network
```

## Modify the MariaDB Configuration File

- Open the `conf/my.cnf` file to change the settings to suit your environment.

## Create and Run a Docker container

```shell
docker-compose up -d
```

or

```shell
docker compose up -d
```