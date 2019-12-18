•      Pattern name:

Channel Patterns (Publish-Subscribe Channel)

•      Visual representation (diagram):
![alt text](https://www.enterpriseintegrationpatterns.com/img/PublishSubscribeSolution.gif)

•      Short definition

When your application has some specific information to share/communicate with, it doesn't throw that data into a messaging system, rather it uses a particular Message Channel so the data gets delivered to the rightful recipient or recipients.

•      Problem it can solve

When you have the same message to send to multiple people, but don't want to send it multiple times.

•      Solution it provides

Copying message in channel and routing it to appropiate consumers.

•      What is it good for

Sending information to multiple consumers.

•      What is it not so good for

When needing to route only to one consumer.

•      One example of implementation

Fanout channel in RabbitMQ.
