**To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:**

# Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
# ReferenceError
 *VARIABLE DOES NOT EXIST This is caused by a variable that is not declared or is out of scope.*
 *VA RIABLE IS UNDECLARED var wi dth = 12 ; var area = width * llt!ftNU! ; ReferenceError: Can ' t find vari able:height*
*NAMED FUNCTION IS UNDEFINED document.write ( randomFunction() ) ; ReferenceError: Can't find variable : randomFunction*

# Syntax Error
SYNTAX IS NOT CORRECT
This is caused by incorrect use of the rules of the
language. It is often the result of a simple typo.
MISMATCHING OR UNCLOSED QUOTES
document .write ("Howdyl );
SyntaxError: Unexpect ed EOF
MISSING CLOSING BRACKET
document .getElementByid('page' I
SyntaxErr or : Expected token ' ) '
MISSING COMMA IN ARRAY
Would be same for missing] at the end
var l ist = ['Item 1', 'Item 2 ' l 'rtem 3'];
SyntaxError: Expected token ']'
MALFORMED PROPERTY NAME
It has a space but is not surrounded by quote marks
user = {f i rstl name: "Ben", lastName: "Lee"};
Synt axError: Expected an identifier but
found 'name ' instead

# 1: DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it. 
# 2: HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.
Sometimes, an error may occur in the script for a
reason beyond your control. For example, you might
request data from a third party, and their server
may not respond. In such cases, it is particularly
important to write error-handling code.
In the latter part of the chapter, you will learn how to
gracefully check whether something will work, and
offer an alternative option if it fails. 
# f you know your code might fail, use try, catch, and finally. Each one is given its own code block.
try {
II Try to execute this code
catch (exception) {
II If there is an exception, run this code
fina lly {
II This always gets executed

# If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
# Debugging is the process of finding errors. It involves a process of deduction.
# The console helps narrow down the area in which the error is located, so you can try to find the exact error.
# JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
# If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 