# Node.js
* Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JS engine and libuv library
* Node programs are not executed in the browser. Node.js is a program we can use to execute JS on our computers. IOW it's a JS runtime
* 301-reading-journal[master]$ node -v
v10.18.1
* npm is JS package manager
* npm and node are designed to automate the process of developing a modern js application
* node.js lets us run js on the server
* node.js is event driven. Everything that happens in node is in reaction to an event!!!
* Node execution model:
  1. Node apps pass async tasks to the event loop, along with a callback
  1. The event loop efficiently manages a thread pool and executes tasks efficiently...
  1. ...and executes each callback as tasks complete
* Downsides
  * errors handled incorrectly can crash the entire process
* Apps suited for node.js
  * Apps that require real-time interaction or collaboration. Good for APIs where you're handling lots of requests that are i/o driven. Streaming sites--node can process files while they're being updated. 
 
