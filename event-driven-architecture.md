# Event Driven Architecture

## Review, Research, and Discussion

### What’s the difference between a FIFO and a standard queue?

A FIFO behaves similarly to a standard queue, but supports odering and exactly-once processing.

### How can the server be assured a message was properly received?

Either receiving a response from the client confirming receipt of a message, or performing a status check at regular intervals.

### What classic design pattern is best represented by event driven programming?

The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. [wiki](https://en.wikipedia.org/wiki/Observer_pattern)

### How do you test an event driven system?

Unit testing, service testing, and end-to-end testing form a system-under-test.

## Terms

**FIFO Queue** - an amazon SQS service that provides for FIFO functionality and exactly-once processing.

**Pub/Sub** - an asynchronous messaging service that decouples services that produce events from services that process events.

## Preparation Materials

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)
