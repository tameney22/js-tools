# Node.js

## Tool Summary

Node.js is an asynchronous event-driven JavaScript runtime environment that is designed to build scalable network applications.

## Useful Links

**Node.js Documentation:**

- <https://nodejs.dev/learn>
- <https://nodejs.org/en/>

**Node.js Tutorials:**

- <https://www.youtube.com/watch?v=RLtyhwFtXQA>
- <https://www.simform.com/blog/what-is-node-js/>

**Demo Links**

- [Plain JavaScript Demo](https://codesandbox.io/s/csci-397-js-pef0b8)
- [Express.js Demo](https://codesandbox.io/s/204q4r408j)

## Presentation Questions:

### What are the goals of Node.js?

The goal of Node.js is to be used for data-intensive real-time applications running across shared devices. It can be used on both the front and backend. It is not a programming language or framework, it is just an environment for programming languages to use. It is also not intended to be used to do heavy computation.

### How does Node.js work?

Uses non-blocking, event-driven I/O to remain lightweight and efficient in the face of data-intensive real-time applications that run across distributed devices. Does so with a single-thread instead of the traditional web-serving techniques where each connection/request spawns a new thread that takes up system RAM and could potentially max out the amount of RAM available. The single-thread method allows node.js to support tens of thousands of concurrent connections in the event loop. A specific library called "Libuv" provides the event loop mechanism and this processing model is majorly based on Javascript event-based model along with the callback mechanism.

- **Asynchronous/Non-blocking thread execution:** Every API of the Node.js library is non-blocking. While waiting for a response for something outside the execution chain, the next tasks in the stack are continuously executed.
- **Event-Driven:** A server build with Node.js uses a notification mechanism called "events" to receive and track responses of previous API requests. Event Loops allow Node.js to execute all the non-blocking operations.

### What do you need to use Node.js? What does it depend on?

To use Node.js you need to first download Node.js which will automatically install NPM. While NPM is not necessarily needed to use Node.js it does make it easier to use and can be very helpful. You can download packages along with Node.js from NPM that will be managed with NPM and extend the usability of Node.js.

### Strengths of the Node.js:

- Open Source
- Great for building fast, scalable network applications
- Capable of handling a huge number of simulatneous connections with high throughput
- Highly scalable
- Operates on a single thread using non-blocking I/O calls
  - Allows for Node.js to support tens of thousands of concurrent connections held in the event loop
- Easy to learn and use
- Fast and efficent
- Strong backend because it runs on V8 JavaScript
- Maintainable

### Limitations of Node.js:

- If you use Node.js for heavy computation it will get rid of basically all of the advantages because it could choke up the single thread and cause problems for all clients as incoming requests would be blocked until the computation was complete.
- You have to download packages so Node.js does not initially come with a robust library system.

### Opportunities of Node.js:

Node.js is a popular selection for many companies like Twitter, Spotify, eBay, Reddit, LinkedIn and so many more.

Since it can be extended with packages you can do mostly anything you can think of with Node.js and the vast number of packages you download can be managed with NPM for ease.

Some examples of packages that can be used are:

- [Express](https://www.npmjs.com/package/express) - Used for HTTP servers
- [Moment](https://www.npmjs.com/package/moment) - Used for used for dates and time
- [Passport](https://www.npmjs.com/search?q=passport) - Used for authentication
- [Socket.io](https://www.npmjs.com/package/socket.io) - Used for bidirectional event-based communication
- [Lodash](https://www.npmjs.com/package/lodash) - Used for delivering modularity, performance, and extras.
- [Forever](https://www.npmjs.com/package/forever) - Used for making a script run continousuly
- [Async](https://www.npmjs.com/package/async) - Used for higher-order functions and common patterns for asynchronous code
- [Mocha](https://www.npmjs.com/package/mocha) - A Simple, flexible, fun JavaScript test framework

### Alternatives/Competitors to Node.js

- [ELIXIR](https://elixir-lang.org/) - Runs tasks simultaneously instead of asynchonously so ELIXIR has a higher concurrency than Node.js
- [ASP.NET](https://www.asp.net/) - Node.js offers more flexibility than asp.net because it allows developers to write code using a multitude of small components rather than configuring a vast number of parameters.
- [PHP](https://www.php.net/) - Ideal for server-side scripting
- [Django](https://www.djangoproject.com/) - A high-level Python web framework that encourages rapid development to facilitate web developers in developing applications timesly and swiftly.

**Other links that might be useful:**

- [https://nodejs.org/en/docs/guides/getting-started-guide/](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [https://en.wikipedia.org/wiki/Node.js](https://en.wikipedia.org/wiki/Node.js).
- [https://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js](https://www.toptal.com/nodejs/why-the-hell-would-i-use-node-js)
- [https://kinsta.com/knowledgebase/what-is-node-js/](https://kinsta.com/knowledgebase/what-is-node-js/)
- [https://stackshare.io/nodejs/alternatives](https://stackshare.io/nodejs/alternatives).
- [https://www.youtube.com/watch?v=CELj-DCB0go](https://www.youtube.com/watch?v=CELj-DCB0go)
- [https://www.youtube.com/watch?v=TlB_eWDSMt4](https://www.youtube.com/watch?v=TlB_eWDSMt4)
