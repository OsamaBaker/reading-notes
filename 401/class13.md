# Message Queues

1. What does it mean that web sockets are bidirectional? Why is this useful?
> Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time

2. Does socket.io use HTTP? Why?
> Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .

3. What happens when a client emits an event?
> The event gets passed to the server through websockets.

4. What happens when a server emits an event?
> each time a peer connects to it.

5. What happens if a client “misses” an event?
> The client will be disconnected.

6. How can we mitigate this?
> We should consider a reconnect.

Socket - A socket is one endpoint of a two-way communication link between two programs running on the network. 

Web Socket - A WebSocket is a persistent bi-directional communication channel between a client (e.g. a browser) and a backend service.

Socket.io - Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

Client - a service made available by a server as part of the client–server model of computer networks. The server is often (but not always) on another computer system, in which case the client accesses the service by way of a network.

Server - A server is a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network.