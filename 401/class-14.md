# Event Driven Architecture

* * Review, Research, and Discussion

* What’s the difference between a FIFO and a standard queue?
- FIFO queues contain many of the same characteristics as ordinary queues, but they also enable sorting and exactly-once processing. FIFO queues have extra characteristics that aid in preventing unintended duplicates from being transmitted by message producers or received by message consumers.


* How can the server be assured a message was properly received?
- You may program your server to get a message received notice when a message is received.


* What classic design pattern is best represented by event driven programming?
- The observer design pattern [source](https://en.wikipedia.org/wiki/Observer_pattern)


* How do you test an event driven system?
- Log everything! Messages may or may not be received, but you can test by using the logs

- Start the application under test.
- Send some input events to the server.
- in the server try to console log each event data.
- Wait until the application has listened to the events been send.
- Assert that the data is logged and as you want.



* * Preview

Which 3 things had you heard about previously and now have better clarity on?
FIFO Queue, event-driven programming and messaging queue.

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Pub/Sub, Design patterns 

What are you most excited about trying to implement or see how it works?
Event Driven Architecture and using AWS 



**FIFO Queue:** FIFO (First-In-First-Out) queues are used to improve communications between applications where the sequence of actions and events is essential or duplicates are not permitted. They have the extra feature of allowing for ordering and exactly-once processing.
**Pub/Sub:** a communications pattern in which message senders, known as publishers, do not design messages to be delivered directly to specific receivers, known as subscribers, but instead organize published messages into classes without knowing which subscribers, if any, may exist. Similarly, subscribers indicate an interest in one or more classes and only get communications that are relevant to them, 
represents the stream of messages (data) to be provided to the subscribing application from a single, unique topic (publisher).
Asynchronous communications is provided via Pub/Sub.
Pub/Sub can be used as messaging middleware or for event intake and delivery in streaming analytics pipelines.

Pub/Sub provides long-term message storage and real-time message delivery while maintaining high availability and consistency of performance at scale.