# FUNCTION DECLARATION
*A function declaration creates a function that you can call later in your code. It is the type of function you have seen so far in this book.*
*In order to call the function later in your code, you must give it a name, so these are known as named functions. Below, a function called area() is declared, which can then be called using its name.*
 **ex**
 function area (width, height)
return width * height;
};
var size= area (3, 4)

# FUNCTION EXPRESSION
*If you put a function where the interpreter would expect to see an expression, then it is treated as an expression, and it is known as a function expression.*
*In function expressions, the name is usually omitted.*
*A function with no name is called an anonymous function. Below, the function is stored in a variable called area. It can be called like any function created with a function declaration.*
**ex**
var area = f unction(width, height) {
r eturn width * height;
} ;
var size = area (3, 4) ;
# LOCAL VARIABLES
*When a variable is created inside a function using the var keyword, it can only be used in that function.*
# GLOBAL VARIABLES
*If you create a variable outside of a function, then it can be used anywhere within the script.*
# Conditional statements allow your code to make decisions about what to do next.
# Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.
# Logical operators allow you to combine more than one set of comparison operators.
# if ... else statements allow you to run one set of code if a condition is true, and another if it is false.
# switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
# Data types can be coerced from one type to another. 
# All values evaluate to either truthy or falsy. There are three types of loop: for, while, and do ... while. Each repeats a set of statements.

# ATTRIBUTE NODES

*The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.* 
# TEXT NODES
*Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.*
# document.write()
The document object's write () method is a simple
way to add content that was not in the original
source code to the page, but its use is rarely advised.
ADVANTAGES
• It is a quick and easy way to show beginners how
content can be added to a page.
DISADVANTAGES
• It only works when the page initially loads.
• If you use it after the page has loaded it can:
1. Overwrite the whole page
2. Not add the content to the page
3. Create a new page
• It can cause problems with XHTML pages that
are strictly validated.
• This method is very rarely used by programmers
these days and is generally frowned upon

# eZement.innerHTML
The i nnerHTML property lets you get/update the
entire content of any element (including markup) as
a string. 

# DOM MANIPULATION
DOM manipulation refers to using a set of methods
and properties to access, create, and update
elements and text nodes. 

# The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
# You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
# Whenever a DOM query can return more than one node, it will always return a Nadel i st.
# From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.
# An element node can contain multiple text nodes and child elements that are siblings of each other.
# In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
# Browsers offer tools for viewing the DOM tree . 
