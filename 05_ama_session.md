# AMA Questions

## Q1. How do you filter data in an API URL?

We can filter data by passing query parameters in the URL, like `?category=electronics&price=50000`.

## Q2. How do you find data in a file using keyboard shortcuts?

We can use Ctrl + F to open the find option and search for specific text inside the file.

## Q3. What is the `fs` module?

The fs module is a Node.js built-in module used to work with files and folders, like reading, writing, updating and deleting files.

## Q4. What is the difference between a process and a thread?

A process is a running program with its own memory, while a thread is a smaller unit inside a process that shares its memory.

## Q5. What is the difference between the DOM and CSSOM?

DOM represents the HTML structure of a webpage, while CSSOM represents the CSS rules and styles applied to the page.

## Q6. What is the difference between `Promise.all()` and `Promise.allSettled()`?

Promise.all() fails when any promise rejects, while Promise.allSettled() waits for all promises and gives the result of each one.

## Q7. When an API requires an API key or token, what are the alternatives to passing them in the API URL?

We can pass them using HTTP headers, such as Authorization or a custom header, instead of exposing them in the URL.

## Q8. What is the difference between `PUT` and `PATCH`?

PUT is generally used to replace the complete resource, while PATCH is used to update only specific fields of a resource.

## Q9. What is polymorphism?

Polymorphism means one interface or method can behave differently depending on the object or class using it.

## Q10. How do we do promise chaining one by one?

We return a promise from `.then()` and attach another `.then()` to it, so each operation runs after the previous one is completed.

## Q11. What are the `find()` and `filter()` methods in JavaScript?

find() returns the first element matching the condition, while filter() returns all elements that match the condition.

## Q12. What is the difference between HTTP and HTTPS?

HTTP sends data without encryption, while HTTPS encrypts the data using SSL/TLS, making communication more secure.

## Q13. What is the difference between `append()` and `appendChild()`?

append() can add text and multiple nodes, while appendChild() adds only one Node object at a time.
