# Class 12 Reading Notes | Readings: Socket.io

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

- Q: What is a Web Socket?

  - A: WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

- Q: Describe the Web Socket request/response handshake and what happens once the connection is established.

  - A: A WebSocket handshake is initiated with a request, for which the server returns a WebSocket handshake response. The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.

- Q: Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

  - A: request

## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

- Q: What does the event handler io. on() do?

  - A: The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.

- Q: Describe some possible proof of life or proof that the code works as expected

  - A:  Console.log is our friend when it comes to proof of life.

- Q: What does socket.emit() do?

  - A: Allows us to create a custom event.

## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

- Q: What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

  - A: WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. Socket.IO is built upon Websockets protocols,

- Q: When would you use Socket.IO?

  - A: Broadcasting

- Q: When would you use WebSockets?

  - A: full-duplex communication on TCP connections.

## [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

- Q: What are a couple of key takeaways from this video?

  - A:  The open system interconnection model included 7 layers.
    - Application Layer (hypertext, remote login, file transfer, email, DNS)
    - Presentation Layer (Apple filling protocol, Citrix)
    - Session Layer (SOCKS, ADSP, NetBIOS, )
    - Transport Layer (TCP, UDP, )
    - Network Layer (IPsec, IPv4, IPv6)
    - Data Link Layer (USB, PCI Express, Link Layer, Ethernet, )
    - Physical layer (PCI Express (physical) USB (Physical) Wi-Fi, Bluetooth, DSL, Ethernet)

## [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

- Q: Translate the gist of this video to a non-technical friend

  - A: TCP Three way handshake. The transmission control protocol is like a user jumping on chrome and wanting to go to myspace... well first the computer asks the server for a connection. The server replies back to the client with SYN-ACK, which stands for synchronization acknowledgment. The server then asks the client to open the connection, to which then the client responds with ACK. The two-way connection is now created.

## Things I want to know more about

HOOKS!