# Event Driven Architecture

1. What’s the difference between a FIFO and a standard queue?
> Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

2. How can the server be assured a message was properly received?
> By having the client emit a “received” event back to the server upon receipt of the message

3. What classic design pattern is best represented by event driven programming?
> Observer pattern.

4. How do you test an event driven system?
> Unit testing.

FIFO Queue - A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle

Pub/Sub - In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic