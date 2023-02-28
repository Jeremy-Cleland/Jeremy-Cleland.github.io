# Class 13 Reading Notes | Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

- Q: Explain to a non-technical recruiter what the Chat Example (above) does.

  - A: Socket.io provides a bi-directional communication channel between a client and a server. The server will get the message and push the messages to all the other clients. The client never sends the message per se, but the server is waiting for an "event" in our case a message. Next, the server broadcasts the message to whomever it was for.

- Q: What proof of life are we getting on the backend from the above app?

  - A: Whatever is console logged, in this case, the backend is logged when a user is connected and disconnected.

- Q: Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

  - A: brodcast

## [Rooms](https://socket.io/docs/v4/rooms)

- Q: What is a room and how might a room be useful?

  - A: A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:

- Q: How do you join a room?

  - A:

``` JS
  io.on("join", (socket) => {
  socket.join(room);
});
```

- Q: how do you leave a room?

  - A:

``` JS
  io.on("leave", (socket) => {
   socket.leave(room);
});
```

## [Namespaces](https://socket.io/docs/v4/namespaces/)

- Q: What is a Namespace and what does it allow you to do?

  - A: A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

- Q: Each namespace potentially has its own what? (hint: 3 things)

  - A:
    - event handlers
    - rooms
    - middlewares

- Q: Discuss a possible use case for separate namespaces

  - A:  A common use may be to separate admin concerns from those of regular users.

## Things I want to know more about

React hooks
