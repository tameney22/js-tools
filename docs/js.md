# Intro To JavaScript

## Tool Summary

JavaScript is a **scripting language** that is one of the backbones of the World Wide Web. Usually it is used in conjunction with HTML (creates the backbone of a webpage) and CSS (useful for styling the page) to make a webpage "come to life". Aside from web pages, it is also used for adding interactivity to web and mobile apps, game development, and building servers.

## Useful Links

#### JavaScript Documentation:

- <https://tc39.es/ecma262/>
- <https://github.com/tc39/proposals>
- <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference>
  > Note: the first link is the official JavaScript language specification documentation. The second link leads to proposals to be added to the specifications, and could be helpful for those who wish to stay on the cutting edge.

#### JavaScript Tutorials:

- <https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics>
- <https://www.javascripttutorial.net/>
- <https://www.youtube.com/watch?v=PkZNo7MFNFg>

#### JavaScript Demos:

-<https://www.w3schools.com/js/js_examples.asp>

## Presentation Questions

### Goals of JavaScript

- **Deliver interactivity** - bring life to static webpages, apps, etc.
- **Lightweight** - designed to maximize speed and efficiency to deliver a seamless user experience.
- **Asynchronous** - scripts that are client-side (on a user's computer) can work even when a user is offline as long as they stay on the same page.

### How does it work?

- In a browser, JavaScript is only executed after HTML and CSS are fully loaded into a DOM (Document Object Model), which allows your scripts to see a live view of your web page. Only after the page is fully loaded is the JavaScript executed, which is what allows the script to modify the existing features of the web page.
- JavaScript can be either interpreted or, in more modern browsers, just in time compiled.
- **Just In Time Compilation** - the browser (or engines like V8) compile the code **as it is being executed.** Each JIT compiler will differ slightly based on the environment, but has three basic components:
  -- The **Monitor**: this component keeps track of how often each statement in your code is run when the interpreter executes the code. Code that is executed often is labeled **warm** and sent to the next level to be compiled and stored.
  -- The **Baseline** Compiler: The warm sections of code are compiled into **bytecode** and run by an interpreter that is optimized for it. Optimization begins by turning code into "stubs".
  -- The **Optimization** Compiler: This compiler then takes over by grouping stubs. This can eliminate the need for things like repeated type checks.
- **Single - Threaded** - JavaScript only has one Call Stack (data structure that keeps track of the steps of a program) so only one thread can run at a time.
- **Dynamic Typing** - types do not need to be declared when variables are.
- **Object - Oriented**

### What do you need to use JavaScript?

Any text editor and a browser is enough to get started! Before beginning to learn JavaScript, learning how to use HTML and CSS is strongly suggested. For use in other contexts than a browser, see the other pages on this website.

### Advantages of JavaScript

- **Speed** - code is lightweight and runs directly on client side, creating maximum speed and efficiency.
- **Simplicity** - especially for a developer with prior programming experience, the learning curve for JavaScript is relatively low.
- **Popularity** - one of the top languages in use currently; huge number of libraries, frameworks, and tools available; lots of resources for support
- **Integration** - JavaScript integrates easily with other languages and increases their potential.
- **Backwards Compatibility** - older conventions and syntax are still supported, protecting old code from breaking
- **Future Potential** - The potential uses for JavaScript are only increasing. For example, libraries like Tensorflow.js are allowing JavaScript developers to enter the machine learning sphere, an area currently dominated by Python.

### Drawbacks of JavaScript

- **Security** - Because JavaScript is usually run client-side, sometimes it can be a vehicle for malware.
- **Confusion**- While maintaining support for older conventions keeps older code functional, it also means that some ideas that were probably not the greatest cannot be completely phased out. This can be confusing for new developers who are trying to learn best practices.
- **Difficulty Debugging** - Although there are some HTML editors that have debugging features for JavaScript, debugging is not as easy or efficient as other languages.

## A Guided Meditation

Is trying to use JavaScript making you want to say "Screw this", but you're not even sure what "this" refers to? Did you not realize your int was being implicitly cast to a string and now want to explicitly cast your laptop out a window? Turn your frustrations into **3 minutes of Zen** that will help you power through the last of your refactoring with this video.

<https://www.youtube.com/watch?v=a7movncpOQc>
