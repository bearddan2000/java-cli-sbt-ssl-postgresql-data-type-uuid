# java-cli-sbt-ssl-postgresql-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A java sbt build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- sbt
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
