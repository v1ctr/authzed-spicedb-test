# Authzed SpiceDB Test

## Run SpiceDB

    docker-compose up

## Install the zed CLI tool

    brew install authzed/tap/zed

## Login to SpiceDB

    zed context set local localhost:50051 "somerandomkeyhere" --insecure

## Importing schema

    zed import schema.yaml

## Validating schema

    zed validate schema.yaml
