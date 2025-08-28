# Question 1 : What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans:getElementById: Selects a single element by its id and returns an Single element or null if does not exists.

getElementsByClassName: Selects elements (multiple) by their class name and returns live HTMLCollection.

querySelector: Selects the first element matching a CSS selector and returns Single element or null if doesn't exists. Useful when there is no id defined.

querySelectorAll: Selects all elements matching a CSS selectorand returns a static NodeList.

# Question 2 : How do you create and insert a new element into the DOM?
Ans: To create a DOM element, we use the Document.CreateElement method and in it, we write the tag that we want to create the element between double quotations or single quotations and if we want to open it in DOM, what we can do is Document.Body. Using this method, we can append an element to the document or inside a DOM element.

# Question 3 : What is Event Bubbling and how does it work?
Ans: Event bubbling is when we use click event or any event on child element then it is first applied on child element then applied on parent element and then applied on grant element then on document then on window and this the Event bubbling.