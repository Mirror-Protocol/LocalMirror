# LocalMirror

🚧 **Under Construction**
## What is LocalMirror?
LocalMirror is a complete Mirror suite containerized with Docker and orchestrated with a simple docker-compose file, designed to make it easy for mirror developers to test out their contracts on a sandboxed environment before moving to a live testnet or mainnet.

## Prerequisits
* Docker and docker-compose
* [LocalTerra](https://github.com/terra-project/localterra)
* mirror-cli for deploying contracts

## How to run
Copy *.json from mirror-cli/data to data directory

> Run LocalTerra first

```sh
docker-compose up
```
