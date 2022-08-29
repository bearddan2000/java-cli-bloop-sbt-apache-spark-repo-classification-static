# java-cli-bloop-sbt-apache-spark-repo-classification-static

## Description
A POC for a java apache spark single node app.
Uses and reads from a flat file a list of
active repos in my github account.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - apache spark

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://www.baeldung.com/apache-spark)
