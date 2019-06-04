# This repo demonstrates how to setup a Mongo primary secondary docker-compose and the official mysql docker image.

## How to use

### Using `docker-compose`
The simplest and the recommended way to configure and run a Mongo server with Docker is to use the [Docker compose](https://docs.docker.com/compose/). Once you have `docker` and `docker-compose` installed on your system (the one on which you'd want to run the Mongo server), copy this [`docker-compose.yml`](https://github.com/Sunil777/docker-compose-mongo-primary-secondry/blob/master/docker-compose.yml) to a folder, and run `docker-compose up -d` to start the Mongo server. Here is a series of commands to run in the terminal to achieve this:

```bash
$ mkdir mongo-docker
$ cd mongo-docker
$ git clone https://github.com/Sunil777/docker-compose-mongo-primary-secondry.git
$ sudo docker-compose up -d
```
