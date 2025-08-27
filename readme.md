  
 Ans 1

  Ans : The difference between getElementById, getElementsByClassName is
  with getElementById we get id and it return Element.
  Moreover, The difference between querySelector / querySelectorAll is
  querySelector select an element and the element which it get first return that. 
  On the other hand querySelectorAll it selects all the elements which mach with the element and it returns NodeList.

 Ans 2

  Ans:  To create a new element into Dom I will create element add that with document 
  like document.createElement('tag') after that i will set content and that element will connect with innerHtml finally i will attached that file in dom with appendChild.

 Ans 3

 Ans: Whenever i click in any element it trigger that element and step by step it fly in the outer elements. Likewise from small elements to parent elements and from parent elements to grandparent elements at the end it goes to. document. It propagating like this way. The way it works is first it works on child element then it will work on parent element.

 Ans 4

 Ans: Event Delegation is a process of JavaScript we not need to set eventListener to the child element instead that we select the parent and add eventListener to that parent.
It is useful because it is memory efficient more clear code and dynamic element support.

Ans 5

Ans: preventDefault() stops the normal Behavior with out using preventDefault the elements propagating among themselves.
stopPropagation() it stops the event bubbling.
Main difference between this two is in preventDefault() Event propagation runs default behavior stops.
However,
In stopPropagation() Event Propagation stops and default behavior not stops it is closed.


