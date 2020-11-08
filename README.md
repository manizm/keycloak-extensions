# Keycloak Extensions

This repository shows how you can extend Keycloak's features.

## Table of content

- [Prerequisites](#prerequesites)
- [Setup](#setup)
- [Custom Event Listener](#custom-event-listener)

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

## Setup

### Start and stop the containers

Before start working you have to start the Docker containers:

```bash
docker-compose up --build --detach
```

After finished working you can stop the Docker containers:

```bash
docker-compose stop
```

The website will be accessible at [http://localhost:8080/](http://localhost:8080/). The default username for the master realm is "admin" and the password "password".

### SMTP Server

In order to test the whole workflow locally, [Mailhog](https://github.com/mailhog/MailHog) is set up and can be configured as SMTP server that catches all outgoing mails. These are the SMTP configurations:

- Host: mailhog
- Port: 1025

All catched emails can be visited at [http://localhost:8025/](http://localhost:8025/).

## Custom Event Listener

//TODO
