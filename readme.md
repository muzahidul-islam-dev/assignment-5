## Question: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

## Answare:

1. getElementById: Select One Element if element using id

2. getElementsByClassName: Select Multiple Element who using same class

3. querySelector: Select matching first element

4. querySelectorAll: Select all matching all elements

## Question: How to create and insert a new element into the DOM

### Answare:

Create heading element:

const newElement = document.createElement("h1");  
newElement.textContent = "Muzahidul Islam";  
document.body.appendChild(newElement);

## Question: What is Event Bubbling and how does it work?

### Answare:

Event Bubbling means an event starts on the target element and then propagates upward through its parent elements to the document.

## Question: What is Event Delegation in JavaScript? Why is it useful?

### Answare:

Delegation: Attaching single event to parent element to handle events for this child elements
useful:

1. Memory saved
2. Can add Element Dynamically

## Question: What is the difference between preventDefault() and stopPropagation() methods?

### Answare:

1. preventDefault(): Use for stop action. like: link, submit, etc.
2. stopPropagation(): Use for stop event from bubbling to parent element.
