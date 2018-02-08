# burrow-docker
Dockerfile, docker image, sample configuration and sample docker-compose for [burrow](https://github.com/linkedin/Burrow)

## Quickstart
1. Start the application
  ```
  docker-compose up -d
  ```
2. localhost:8000 is ready to use

## Usage
### Dockerfile
* Apply [multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/)
* [Docker image](https://hub.docker.com/r/dangnguyen/burrow-docker/)

### Burrow
What we need to read to understand burrow

* https://github.com/linkedin/Burrow/wiki
* https://github.com/linkedin/Burrow/wiki/Configuration
* https://github.com/linkedin/Burrow/wiki/HTTP-Endpoint
* https://github.com/linkedin/Burrow/wiki/Consumer-Lag-Evaluation-Rules

Example [configuration](https://github.com/dangkaka/burrow-docker/blob/master/configs/burrow.toml)

### Reference
* Docker-compose uses [Kafka cluster docker](https://github.com/wurstmeister/kafka-docker)
