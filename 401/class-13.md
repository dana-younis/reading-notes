# Message Queues

* * Review, Research, and Discussion

* What does it mean that web sockets are bidirectional? Why is this useful?
- Once a connection is established between the web client and the server, data may be sent back and forth on the same port in both directions. This is advantageous since it conserves ports and sockets.

* Does socket.io use HTTP? Why?
- It does not utilize HTTP by default, but it was created with HTTP as a fallback alternative in mind. It is compatible with HTTP in that web socket servers and HTTP servers can coexist on the same TCP port.

* What happens when a client emits an event?
- The event is delivered to the server, and all listeners connected to that socket and listening for it are fired.

* What happens when a server emits an event?
- Client-side listeners who are connected and listening for that event will be triggered.

* What happens if a client “misses” an event?
- In a Windows environment, the computer could explode. Otherwise, the event is ignored.

* How can we mitigate this?
- Have handlers that catch these and decide based on other state what to do with them. In a Windows environment, you're out of luck.

* * Preview
* Which 3 things had you heard about previously and now have better clarity on?
TCP, Socket.io and web sockets.

* Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Packets, OSI model and UDP

* What are you most excited about trying to implement or see how it works?
real-time messaging apps

* * Preparation Materials
**Socket:** a computer network endpoint for sending and receiving data. [source](https://en.wikipedia.org/wiki/Network socket)


**Web Socket:** A two-way communication mechanism that allows servers and clients to communicate and exchange data at the same time. [source] (https://www.tutorialspoint.com/websockets/websockets overview.htm)


**Socket.io:** a node library for bidirectional, real-time communication. It works on every platform, browser, or device, with equal emphasis on dependability and speed. [source](https://socket.io/)


**Client:** the entity requesting data in a transaction.


**Server:** the entity that sends data in an example


**TCP:** It is well-known for delivering dependable and error-free communication between end systems. It conducts data sequencing and segmentation. It also includes an acknowledgement function and regulates data flow via a flow control mechanism. It is a very effective protocol, but it has a lot of overhead as a result of these qualities. Increased overhead equals higher costs. TCP contains techniques for dealing with many of the issues associated with packet-based communications, such as missing packets, out-of-order packets, duplicate transmissions, and damaged packets.
TCP is appropriate for real-time programs that must preserve data.


**UDP:**User Datagram Protocol: is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. It speeds up transmissions by enabling the transfer of data before an agreement is provided by the receiving party. it is suitable for streaming and gaming.


* Rooms
A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.


### OSI Model:
(Open Systems Interconnection) is a model that describes seven layers that computer systems use to communicate over a network. these layers are:
(Please Do Not Throw SUSAGE PIZZA Away)
 1. Application 
 2. Presentation
 3. Session
 4. Transport
 5. Network 
 6. Data Link
 7. Physical 