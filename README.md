# Project_Emergency-Hotline
# 1.
Get Element By ID can only take a single element. For example, suppose I have many tags in my HTML file. If I call Document Get Element By ID and pass my ID as a parameter, it will grab only the first element and ignore the rest of the elements.

getElementsByClassName When we use this, we can access all the common classes and return us an html collection.

querySelector selects only one element that matches a CSS selector.Unlike querySelectorAll ,it only returns the 1st element that satisfies the CSS selector.

querySelectorAll selects all the element that matches a CSS selector.It returns a static node list.

# 2.

To create a DOM element, we use the Document.CreateElement method and to insert the new element in the DOM, appendChild() can place it at the end of a parent, prepend() can place it at the beginning, and insertBefore() to position it before a specific reference element.

# 3.

Event bubbling is when we use click event or any event on child element then it is first applied on child element then applied on parent element and then applied on grant element then on document then on window and this the Event bubbling.

# 4.

Event Delegation is a method that we can use to get rid of the previous event bubbling, like before when we clicked on an element, it went from that element to its parent element, then to its grand element, then to the document or window, and if we use Event Delegation, then it will only apply the event to the element that is targeted.

# 5.

When we work with an HTML form and submit the form, it automatically reloads, and to stop it, we use the Prevent default() method and we use the stopPropagation() so that when we fire an event, it does not go to the parent.
