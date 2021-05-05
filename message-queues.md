# Message Queues

## Review, Research, and Discussion

### What does it mean that web sockets are bidirectional? Why is this useful?

It means that sockets are 'Full-Duplex', meaning that both server and client can both send and receive information while the connection is open.

### Does socket.io use HTTP? Why?

Yes, socket.io uses HTTP for both fallbacks for tcp events, and to support for functions like namespaces and rooms [src](https://stackoverflow.com/questions/37836130/socket-io-why-does-it-need-an-http-server#37838306)

### What happens when a client emits an event?

The server receives the event as a .on('event', callback) property.

### What happens when a server emits an event?

The clients receive the event as above.

### What happens if a client “misses” an event?

Unhandled events are simply ignored.

### How can we mitigate this?

By creating listeners for all events, then deciding based on some other state whether to do anything with the event.

## Terms

**Socket** - one of the endpoints in a two-way data sharing connection over TCP.

**Web Socket** - communications protocol dictating full duplex communication over a TCP connection.

**Socket.io** - javaScript library for handling realtime communications with web sockets.

**Client** - Party connecting to a server for data exchange.

**Server** - Party connecting to a client, handling management and relay of data exchange.

**OSI Model** - Open Systems Interconnection model characterizes and standardizes the communications protocol of the internet in 7 layers.

**TCP Model** - Transmission Control Protocol model is a concise version of the OSI model for describing communication procedures. 4-layers.

**TCP** - the Transmission Control Protocol is the protocol used on top of IP to support reliable transmission of data between two parties by requiring an established connection between sender and receiver.

**UDP** - User Datagram Protocol is another IP protocol that does not require an established connection channel before sending data.

**Packets** - a formatted unit of data. Essentially the smallest unit of data passed around the internet.

## linky

[Socket.io Chat Example](https://socket.io/get-started/chat/)

[Rooms and Namespaces](https://socket.io/docs/v3/rooms/index.html)

[Socket.io Emit Cheatsheet](https://socket.io/docs/v3/emit-cheatsheet/index.html)
