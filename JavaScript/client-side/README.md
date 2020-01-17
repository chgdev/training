# Client Side JavaScript

## What is the global window object?

## What is the global document object?

## How do retrieve an element from the DOM using the global document object? Give an example of selecting and element by an id and then by a class.

## How do you retrieve multiple elements from te DOM using the global document object? Give an example of selecting elements by a tag and then by a class.

## How do you add a click event to a button? Write an example below.

## How do you get the attributes of an HTMLElement?

## What are some of the properties of HTMLElement?

## How do you get the parent element of a selected element? child element? the children elements? sibling elements? ancestor element?

## How do you add an element to the DOM via the global document objet?

## How do you add styles to a selected element in the DOM? Give an example below.

## How do you add css classes to a selected element in the DOM? Given an example below.

## How do you create an html element and insert it into the DOM?

## What is the difference between using the innerHTML property to add elements, insertAdjacentHTML, and appendChild with document.createElement?

## What is the difference between append and prepend on HTMLElements?

## How do you remove an html element from the DOM?

## How do you log to the console of the browser?

## How do you send an alert to the user in the browser?

## How do you add things to the local storage of your browser?

## How do you get the size of the browser window?

## alert is a function on the window object, but you call call it as if it were a global function, why does this work?

## What are Element Nodes and Text Nodes, and what are the differences?

## How do you access `data-*` attributes from HTMLElements? Give an example of how to read/write them to the DOM elements.

## What is the template tag in HTML used for?

## What is the window.location property used for? List information that this property gives you.

## How do you navigate to another website using the location property?

## What information does the window.history give you? How can you use the property to control navigation?

## What information does the window.navigator property give you?

## How can you tell what browser the user is currently using?

## Intermediate

### What is webpack and what does it do? Are there other tools that do the same thing?

### Why do we ensure that our JavaScript code has been bundled when adding it to the index.html?

### How can you use ES6 across browsers? Take into consideration that IE does not support it fully.

### How do you add a script to the DOM dynamically? When would this be useful?

## Events

### What types of events can you listen to for an HTMLElement? List as many as you can find.

### With the MouseEvent class, for example, what properties does it expose to you?

### How do you listen to an event on a selected HTMLElement?

### What is the difference between `element.onclick(<function>)` and `element.addEventListener('click', <function>)`? Why would you use one over the other?

### How do you remove an event listener from a selected element? Give a code example below.

### What does calling preventDefault on an event do? Give a use case for this function.

### What does calling stopPropagation on an event do? Give a use case for this function.

### What is the difference between stopImmediatePropagation and stopPropagation?

### What are polyfills? How do they allow you to use cutting edge features that are not supported across multiple browsers?

### Why should you never put database connection strings or secrets in your frontend code?

### What are Cross-Site Scripting Attacks (XSS)? Are there any libraries that can help mitigate this issue?

### What are Cross-Site Request Forgery (CSRF)?

### What are different things that affect the start up time of your website? Meaning what can slow down the time that it takes for your website to load?

### Why can DOM operations be expensive?

### Why is it important to measure and audit the performance of your website before making optimizations?

### What are ways to measure the performance of your website?

### Why should you measure the performance of your production ready build of your websites vs the dev version?

### How can you simulate a slower connection speeds in the browser?

### How can you simulate slower CPU speeds in the browser?

### How can you see the performance of your JavaScript code in the browser?

### How can you run the production version of your website while also loading the source maps of your application?

### Why would you create multiple webpack config files?


### How can you see what code is not being used from the Network tab? How can you improve this through lazy loading?

### How can you use jsperf to test the performance of your JavaScript code? 

### How can the Memory Tab be used to find memory leaks?

### Why should you add third party libraries to the bundle instead of using a CDN?3


## Resources

- https://developers.google.com/web/fundamentals/performance/rendering/optimize-javascript-execution
- https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/reference
- https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency
- https://github.com/expressjs/compression
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control
- https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching
- https://wp-rocket.me/blog/different-types-of-caching/
- https://developers.google.com/web/fundamentals/performance/http2