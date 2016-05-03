Docker image to run Hive
===============================

## Current Version
* Apache Hive
* PostgreSQL 9.3 (Hive metastore backend)

## Pull the image

docker pull pandut/docker-hive

## Run the image

docker run -itP pandut/docker-hive /etc/hive-bootstrap.sh -bash
