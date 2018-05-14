# Dockerfile: mongodb & mongohacker

## how to run mongodb with mongo-hacker on docker

look the Dockerfile

## how to create a new user on mongodb

db.createUser({ user: "admin", pwd: "admin", roles: [ "readWrite", "dbAdmin" ]})
