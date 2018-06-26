Introduction (pp. 1-10)

**# Chapter 1 : The ABC of Programming (pp. 11-52)**

C: How do I write a script for a web page?
- It is best to keep JavaScript code in its own JavaScript file.  JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.
- The HTML &lt;script&gt; element is used in HTML pages to tell the browser to load the JavaScript file (rather like the &lt;link&gt; element can be used to load a CSS file).
- If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.

// Single-line comment
/* Multi-line
   comment */

**# Chapter 2 : Basic JavaScript Instructions (pp. 53-84)**
- A script is made up of a series of statements.  Each statement is like a step in a recipe.
- Scripts contain very precise instructions.  For example, you might specify that a value must be remembered before creating a calculation using that value.
- Variables are used to temporarily store pieces of information used in the script.
- Arrays are special types of variables that store more than one piece of related information.
- JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
- Expressions evaluate into a single value.
- Expressions rely on operators to calculate a value.

**# Chapter 3 : Functions, Methods & Objects (pp. 85-144)**
- Functions allow you to group a set of related statements together that represent a single task.
- Functions can take parameters (information required to do their job) and may return a value.
- An object is a series of variables and functions that represent something from the world around you.
- In an object, variables are known as properties of the object; functions are known as methods of the object.
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
- JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
- Arrays and objects can be used to create complex data sets (and both can contain the other).

**# Chapter 4 : Decisions and Loops (pp. 145-182)**
- Conditional statements allow your code to make decisions about what to do next.
- Comparison operators (===, !==, ==, !=, &lt;, &gt;, &lt;=, =&gt;) are used to compare two operands.
- Logical operators allow you to combine more than one set of comparison operators.
- if...else statements allow you to run one set of code if a condition is true, and another if it is false.
- switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
- Data types can be coerced from one type to another.
- All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and do...while. Each represents a set of statements.

**# Chapter 5 : Document Object Model (pp. 183-242)**
- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one node, it will always return a NodeList.
- From an element node, you can access and update content using properties such as textContent and innerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree.

**# Chapter 6 : Events (pp.243-292)**
- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
- When an event occurs on an element, it can trigger JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
- You can use event delegation to monitor for events that happen on all of the children of an element.
- The most commonly used events are W3C DOM events, although there are others in the HTML5 specification as well as browser-specific events.

**# Chapter 7 : jQuery (pp. 293-366)**
- jQuery is a JavaScript file you include in your pages.
- Once included, it makes it faster and easier to write cross-browser JavaScript, based on two steps.
  1. Using CSS-style selectors to collect one or more nodes from the DOM tree.
  2. Using jQuery's built-in methods to work with the elements in that selection.
- jQuery's CSS-style selector syntax makes it easier to work with. It also has methods that make it easier to traverse the DOM.
- jQuery makes it easier to handle events because the event methods work across all browsers.
- jQuery offers methods that make it quick and simple to achieve a range of tasks that JavaScript programmers commonly need to perform.

**# Chapter 8 : Ajax & JSON (pp. 367-408)**
- Ajax refers to a group of technologies that allow you to update just one part of the page (rather than reload a whole page).
- You can incorporate HTML, XML, or JSON data into your pages. (JSON is becoming increasingly popular.)
- To load JSON from a different domain, you can use JSONP but only if the code is from a trusted source.
- jQuery has methods that make it easier to use Ajax.
- .load() is the simplest way to load HTML into your pages and allows you to update just a part of the page.
- .ajax() is more powerful and more complex. (Several shorthand methods are also offered.)
- It is important to consider how the site will work if the user does not have JavaScript enabled, or if the page is not able to access the data from a server.

**# Chapter 9 : APIs (pp. 409-448)**
- APIs are used in browsers, scripts, and by websites that share fuctionality with other programs or sites.
- APIs let you write code that will make a "request", asking another program or script to do something.
- APIs also specify the format in which the "response" will be given (so that the response can be understood).
- To use an API on your website, you will need to include a script in the relevant web pages.
- An API's documentation will usually feature tables of objects, methods, and properties.
- Providing you know how to create an object and call its methods, access its properties, and respond to its events, you should be able to learn any JavaScript API.

**# Chapter 10: Error Handling & Debugging (pp. 449-486)**
- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.

**# Chapter 11: Content Panels (pp. 487-526)**
- Content panels offer ways to show more content within a limited area.
- Popular types of content panels include accordions, tabs, photo viewers, modal windows, and sliders.
- As with all website code, it is advisable to separate content (HTML), presentation (CSS), and behavior (JavaScript) into different files.
- You can create objects to represent the functionality you want (as with the modal window).
- You can turn functions into jQuery plugins that allow you to re-use code and share it with others.
- Immediately invoked function expressions (IIFEs) are used to contain scope and prevent naming collisions.

**# Chapter 12: Filtering, Searching & Sorting (pp. 527-566)**
- Arrays are commonly used to store a set of objects.
- Arrays have helpful methods that allow you to add, remove, filter, and sort the items they contain.
- Filtering lets you remove items and only show a subset of them based on selected criteria.
- Filters often rely on custom functions to check whether items match your criteria.
- Search lets you filter based upon data the user enters.
- Sorting allows you to reorder the items in an array.
- If you want to control the order in which items are sorted, you can use a compare function.
- To support older browsers, you can use a shim script.

**# Chapter 13: Form Enhancement & Validation (pp. 567-622)**
- Form enhancements make your form easier to use.
- Validations lets you give users feedback before the form data is sent to the server.
- HTML5 introduced new form controls which feature validation (but they only work in modern or mobile browsers).
- HTML5 inputs and their validation messages look different in various browsers.
- You can use JavaScript to offer the same functionality as the new HTML5 elements in all browsers (and control how they appear in all browsers).
- Libraries like jQuery UI help create forms that look the same across different browsers.
- Regular expressions help you find patterns of characters in a string.

**# Index (pp. 623-634)**

**Try out & download the code in this book www.javascriptbook.com**
