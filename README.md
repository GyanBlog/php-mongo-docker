# php-mongo-docker
Write php code that connect to mongo db. This has a Dockerfile, which prepares image to have mongo pre-installed.

# Reference
https://www.gyanblog.com/gyan/47-how-connect-php-docker-container-mongo-db-docker-container

# description
This dockerfile takes base image as php:5-apache, and installs mongo dependencies. So, now you have pre-installed mongo dependencies, simply write php code that connects to mongo db.
Note: This doesn't deal with running Mongo instance.

For complete end to end usage with mongo db, visit: https://www.gyanblog.com/gyan/47-how-connect-php-docker-container-mongo-db-docker-container

# How to build docker image
docker build -t <your desired name>:version .
