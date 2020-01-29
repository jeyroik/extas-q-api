# extas-q-api

API package for quality.

# install

## install plugins

`# vendor/bin/extas i`

## create api operations

`# vendor/bin/extas jsonrpc -s src/configs/extas.json -e 1`

## install api operations

`# vendor/bin/extas i`

# usage

## run web server

`# php -S 0.0.0.0:8080 -t vendor/jeyroik/extas-jsonrpc/src/public`


## operations list

`curl -X POST localhost:8080/specs -d "{\"method\":\"operation.all\", \"id\":\"request id\"}"`

## quality crawling

`# vendor/bin/extas q-c`