# Socket.io
* Review, Research, and Discussion
1. What is the benefit of transforming data into packets?

* Packet-based networks are more cost-effective, efficient, and scalable networks for content delivery. 

2. UDP is often refereed to as a connectionless protocol. Why is this?
* This is because UDP doesn't establish a connection before sending data. It just send.
3. Can a socket server application have multiple socket connections?
* Yes, and the maximum number of sockets is 65535.
4. Can a socket connection application be connected to multiple socket servers?
* Yes, you can separate out the incoming socket.io and have separate socket.io server instances.
5. Can an application be both a socket server and a socket connection?
* Yes but you would need two different ports.


* Preview
1. Which 3 things had you heard about previously and now have better clarity on?
* Everything in the previews were very new to me.
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
*
 WebSockets and Socket.IO
 TCP
 Open System Interconnection Model (OSI Model)

3. What are you most excited about trying to implement or see how it works?
* I'm excited to learn more about WebSockets/Socket.IO. It seems like they will be super useful.


## Document the following Vocabulary Terms


* **Observer Pattern:** is a pattern in the program architecture in which an object called the subject keeps a list of its dependents, called observers, and automatically notifies them of any changes of status, generally by using one of its methods.

* **Listener:** The event handler is configured to react to an input or signal. Java and JavaScript are frequently the word event listener.

* **event handler:** is an asynchronous Callback Routine, which handles the incoming inputs of a program (events).

* **Event Driven Programming:** igm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.

* **Event Loop:** is a construct for programming or design that waits for and sends out events or messages in the program. The event loop operates by requesting an internal or external 'event provider' (which usually pauses the request until an event has occurred) ("dispatches the event").

* **Event Queue:** is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system.

* **Call Stack:** a mechanism for an interpreter to keep track of its place in a script that calls multiple functions - what function is currently being run and what functions are called from within that function.

* **Emit/Raise/Trigger:**  in event-driven programming, emit sends a message to trigger a response and raise an event

* **Emit:** Emit’s job is to trigger named event(s) which in turn cause functions called listeners to be called.

* **Database:** The data gathered is structured and typically electronically stored and retrieved via the computer system. Where databases are more sophisticated, formal design and modeling approaches are typically applied.

## Preparation Materials

* **WebSocket:** is a computer communication protocol that provides full duplex channels of communication over a single TCP connection. The IETF standardized the WebSocket protocol in 2011 and the W3C standardized the WebSocket API on the Web IDL.

Socket.IO allows two-way event-based communication in real-time. It operates on all platforms, browsers or devices with a same focus on stability and performance. The WebSockets API (customer side) and Node.j's Socket.IO are built. It's one of the library's most reliable (Node Package Manager).