# Reflection Modul 9
Ragnall Muhammad Al Fath
2306210550 / AdPro B
---

### 1. What is amqp?

AMQP (Advanced Message Queuing Protocol) is an open standard protocol for message-oriented middleware. It enables applications to communicate by exchanging messages regardless of programming language, making it ideal for distributed systems.

### 2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?

First guest: Username for authentication
Second guest: Password for authentication
localhost:5672: Where the AMQP broker (like RabbitMQ) is running
localhost: the local machine
5672: standard AMQP port
This connection string instructs your application to connect to an AMQP broker running locally using default credentials.