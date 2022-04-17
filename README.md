# Steps to run

1. docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management

1. javac -cp amqp-client-5.7.1.jar Send.java Recv.java

1. java -cp .:amqp-client-5.7.1.jar:slf4j-api-1.7.26.jar:slf4j-simple-1.7.26.jar Recv

1. java -cp .:amqp-client-5.7.1.jar:slf4j-api-1.7.26.jar:slf4j-simple-1.7.26.jar Send

Source: https://www.rabbitmq.com/tutorials/tutorial-one-java.html
