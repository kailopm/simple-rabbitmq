# RabbitMQ Simple App

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

Sample application to demonstrate the rabbitmq workflows with just producer, consumer

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes

### Prerequisites
1. npm
2. nodejs
3. docker
4. docker-compose

## Installation <a name = "usage"></a>

```bash
npm init
npm install amqplib mysql uuid
docker-compose up -d --build
```

Create phpMyadmin table order

## Usage <a name = "usage"></a>

Access using the URL http://localhost:15672 (RabbitMQ)
Access using the URL http://localhost:15672 (phpMyAdmin)


```bash
node producer.js # Send object into queue
```
![alt text](img/rabbit_1.png)
![alt text](img/rabbit_2.png)

```bash
node consumer.js # Send object into database
```