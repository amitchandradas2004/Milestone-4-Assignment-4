# Assignment - 4

## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

getElementById(id)  
It selects a single element by its ID. It always returns one element.

getElementsByClassName(className)  
It selects multiple elements by their class name. It returns a live HTMLCollection, which means it updates automatically if the DOM changes.

querySelector(selector)  
It selects the first element that matches a CSS selector. It returns a single element.

querySelectorAll(selector)  
It selects all elements that match a CSS selector. It returns a static NodeList, which does not update automatically when the DOM changes.


---

### 2. How do you create and insert a new element into the DOM?

To create and insert a new element into the DOM, we use document.createElement() and appendChild().

Example:

```javascript
const newDiv = document.createElement("div");
newDiv.textContent = "Hello World";
newDiv.className = "myClass";

document.body.appendChild(newDiv);
```

First, we create the element.  
Then we add content or class to it.  
Finally, we insert it into the DOM using appendChild().


---

