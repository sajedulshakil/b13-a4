1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: There are many differences between getElementById, getElementsByClassName, and querySelector / querySelectorAll . Differences given below: 

1/ getElementById: (id) returns a single element. (id) must be unique.
2/ getElementByClassName: It selects multiple elements by class name. Here must use looping. Returns an html collection.
3/ querySelector: This select first matching element using css selector. It returns only first match.
4/ querySelectorAll: It selects all matching elements using css selector. It returns nodelist. Can be use forEach.

2. How do you create and insert a new element into the DOM?

Ans: First of all create a new element by using div (document.createElement(div)) and Secondly, select the parent element and then appendChild a newdiv.

3. What is Event Bubbling? And how does it work?

Ans: Event bubbling is a behavior of the javascript DOM. Where an event such as a click starts at the element where it occurs and then gradually propagates upward to its parent, then grandparent and finally up to the document

4. What is Event Delegation in JavaScript? Why is it useful?

Ans: Event delegation in javascript is a technique where you attach a single event listener to a parent element instead of adding separate listeners to multiple child elements. The parent element then handles events triggered by its children using the concept of event bubbling.

It's very useful for many reasons. These reasons given below:-
1/ Only use one listener instead of many
2/ Managing all child events in one place
3/ It reduces repetitive event binding 

5. What is the difference between preventDefault() and stopPropagation() methods?

Ans: preventDefault() : This method prevents the default behavior of an event. For example, clicking on an <a> tag normally loads a new page. If preventDefault() is used, the link will not work.

stopPropagation() : This method stops event bubbling. In other words, the event will not reach the parent element.