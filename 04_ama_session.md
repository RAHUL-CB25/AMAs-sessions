# AMA Questions

### Q1. Name some methods of the console object.
Answer: Some common methods are console.log(), console.error(), console.warn(), console.table() and console.clear().

### Q2. What is the difference between Promise.any() and Promise.race()?
Answer: Promise.any() returns the first fulfilled promise. Promise.race() returns the first promise that settles, whether fulfilled or rejected.

### Q3. What is localStorage?
Answer: localStorage is used to store data in the browser until we manually clear it. Data is stored as key-value pairs.

### Q4. What is a function?
Answer: A function is a block of code used to perform a specific task. We can call it whenever we need it.

### Q5. How do you clear a setInterval()?
Answer: We use clearInterval() to stop a running interval.
Example: clearInterval(intervalId);

### Q6. What is git revert?
Answer: git revert is used to undo changes of a previous commit. It creates a new commit without deleting the old commit.

### Q7. What is slicing in Python?
Answer: Slicing is used to get a part of a string, list or tuple. Example: arr[1:4] gets elements from index 1 to 3.

### Q8. What are error-first callbacks?
Answer: Error-first callback is a common Node.js pattern where the first parameter is for error and second is for result. Example: callback(error, data).

### Q9. What is asynchronous programming?
Answer: Asynchronous programming allows code to run without waiting for a long task to finish. It helps JavaScript handle tasks like API calls and file operations.

### Q10. What does findIndex() return if the element is not present?
Answer: findIndex() returns -1 if no matching element is found.

### Q11. What is the full form of MDN?
Answer: MDN stands for Mozilla Developer Network. It is now commonly known as MDN Web Docs.

### Q12. How does Promise.allSettled() work?
Answer: Promise.allSettled() waits for all promises to finish, whether they are fulfilled or rejected. It returns the status and result of every promise.