# forms 


**There are several types of form controls that you can use to collect information from visitors to your site.**
# like
**ADDING TEXT:**
*Text input (single-line) Used for a single line of text such as email addresses and names.*
**Text area (multi-line)** 
*Text area (multi-line) For longer areas of text, such as messages and comments*

**Password input**
*Like a single line text box but it masks the characters entered.*



# Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.
# Information from a form is sent in name/value pairs.
# Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
# HTML5 introduces new form elements which make it easier for visitors to fill in forms.


# The list-style-type property
 allows you to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the <ol>, <ul>, and <li>
elements.
Unordered Lists
For an unordered list you can use
the following values:
 none
 disc
 circle
 square

# If you have empty cells in
your table, then you can use
the empty-cells property to
specify whether or not their
borders should be shown.
Since browsers treat empty cells
in different ways, if you want to
explicitly show or hide borders
on any empty cells then you
should use this property.
It can take one of three values:
show
This shows the borders of any
empty cells.
hide
This hides the borders of any
empty cells.
inherit
If you have one table nested
inside another, the inherit
value instructs the table cells to
obey the rules of the containing
table 

# In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
# List markers can be given different appearances using the list-style-type and list-style image properties.
# Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
# Forms are easier to use if the form controls are vertically aligned using CSS.
# Forms benefit from styles that make them feel more interactive.

# events 

When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 

1
Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. You do this using a
DOM query (see Chapter 5). 

2
Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
The previous two pages showed
a selection of the popular events
that you can monitor for. 

3
State the code you want
to run when the event
occurs.
W hen the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function.

*(element .onevent functionName ;
ELEMENT EVENT CODE
DOM element Event bound to node(s) Name of function to call (with
node to target preceded by word "on" no parentheses following it))*

The addEventli stener ()
method takes three properties:
i) The event you want it to listen
for. In this case, the b 1 ur event.
ii) The code that you want it
to run when the event fires.
In this example, it is the
checkUsername (} function. Note
that the parentheses are omitted
where the function is called
because they would indicate that
the function should run as the
page loads (rather than when the
event fires) 


(If the browser supports
addEventlistener(): if (el .addEventlistener) {
Run the code inside
these curly braces
If it doesn't, do
something else:
Run the code inside
these curly braces
el .addEventlistener('blur', function() {
checkUsername(5);
}, false);
} else {
}
el .attachEvent('onblur', function() {
checkUsername(5);
} ) ; )


# Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
# Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
# When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
# You can use event delegation to monitor for events that happen on all of the children of an element.
# The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.