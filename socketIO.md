# Socket.io

## Review, Research, and Discussion

### What is the benefit of transforming data into packets?

By transforming data into packets, you reduce the overall data size of each individual transfer which allows for networks to accomidate lower or various bandwidths, and easier handling of re-sending data if a connection is interrupted.

### UDP is often refereed to as a connectionless protocol. Why is this?

UDP does not check for a connection before it sends data, it just sends it. UDP is a loudspeaker, where TCP is a telephone.

### Can a socket server application have multiple socket connections?

Yes, using a socket fork to listen for multiple sockets.

### Can a socket connection application be connected to multiple socket servers?

Yes, but must listen on a single port.

### Can an application be both a socket server and a socket connection?

Yes, sockets support both input and output on a single connection.

## Terms

Observer Pattern - The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. [WIKI](https://en.wikipedia.org/wiki/Observer_pattern)

Listener - an open port on a network that waits for a client to connect to the port.

Event Handler - code that is associated with a particular event.

Event Driven Programming - a programming paradigm where the flow of the program is driven by external events.

Event Loop - the javaScript concurrency model which handles running the program, waiting for events, scheduleing and executing queued sub-tasks.

Event Queue - a queue used to store sub-processes that are kicked off by the event loop. Handles the storage and order of sub-processes.

Call Stack - a stack formation that handles the active sub-processes in a program.

Emit/Raise/Trigger - the method the the JS event uses to trigger a given event across a program.

Subscribe - a method that listens for a specific event triggered by another class.

database - a persistent data storage and organization model.

## Links

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

[Socket.io Documentation](https://socket.io/docs/v4/index.html)

[Socket.io Server API](https://socket.io/docs/v3/server-api/index.html)

[Socket.io Client API](https://socket.io/docs/v3/client-api/index.html)

[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)
