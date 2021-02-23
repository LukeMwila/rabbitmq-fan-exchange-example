# RabbitMQ Fanout Exchange Example (JavaScript)

Basic example of a fanout exchange implementation in RabbitMQ using JavaScript.

## Prerequisites

Install [RabbitMQ](https://www.rabbitmq.com/download.html) on your local machine.

Install [NodeJS](https://nodejs.org/en/) which will come with npm.

## Install Dependencies

Run `npm install` to install amqplib as specified in the package.json file.

## Start Application

Run `node consumers.js > logs_from_rabbitmq.log`. This will save any consumed messages to the log file. After that, run either `npm start` or `node index.js` to initiate the publisher and send the message to the exchange named logs.
