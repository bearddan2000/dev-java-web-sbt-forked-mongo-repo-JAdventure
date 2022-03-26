# dev-java-web-sbt-forked-mongo-repo-JAdventure

## dev-Description
A POC for REST web service using mongodb.
Creates a user with credentials.

Uses spring's mongorepository.

## dev-Tech stack
- java
- sbt
  - mongo connector
- mongo

## dev-Docker stack
- mongodb:latest
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## dev-To run
`sudo ./install.sh -u`
- Endpoints
  - localhost/weapons/
  - localhost/weapons/name/shiv

## dev-To stop
`sudo ./install.sh -d`

## dev-For help
`sudo ./install.sh -h`

## dev-Credit
- [Data from JAdventure text game](https://github.com/Progether/JAdventure.git)
- [Code concept](https://github.com/ragcrix/StudentInformationSystem.git)
