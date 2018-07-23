# MEAN Stack using Docker, Docker Images and Docker Compose

This project is a complete example of the MEAN stack and run application on a single command, No need to run the Noder Server for Angular, APIs and Mongodb separately.

Also by using docker images you can have Client or Server code based on the different version of node.

## Mongo DB Image

Download mongodb image: `docekr pull mongo`

Update the connection string like below:

if using mongo db image :
`"connectionString":"mongodb://database/mean-docker"`

If running mongodb remotely (Like hosted db on mlab) :
`"connectionString": "mongodb://username:password@ds056789.mlab.com:56789/nksmongo"`

## Angular

AngularClient folder contains the Angular UI App

## NodeJs Image

Download mongodb Nodejs: `docekr pull node:10.7.0-alpine`

## Docker Compose

To run the project run below command:

`docker-compose up --build`
