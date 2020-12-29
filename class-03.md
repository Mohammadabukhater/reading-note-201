# HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).
# They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).
# There are three types of HTML lists: ordered, unordered, and definition.
# Ordered lists use numbers.
# Unordered lists use bullets.
# Definition lists are used to define terminology.
# Lists can be nested inside one another.
# There are properties to control the choice of font, size, weight, style, and spacing.
# There is a limited choice of fonts that you can assume most people will have installed.
# If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
# You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.
# You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.
**ex**
# <!DOCTYPE html>
<html>
<head>
 <title>Text</title>
 <style type="text/css">
 body {
 padding: 20px;}
 h1, h2, h3, a {
 font-weight: normal;
 color: #0088dd;
 margin: 0px;}
 h1 {
 font-family: Georgia, Times, serif;
 font-size: 250%;
 text-shadow: 2px 2px 3px #666666;
 padding-bottom: 10px;}
 h2 {
 font-family: "Gill Sans", Arial, sans-serif;
 font-size: 90%;
 text-transform: uppercase;
 letter-spacing: 0.2em;}
 h3 {
 font-size: 150%;}
 p {
 font-family: Arial, Verdana, sans-serif;
 line-height: 1.4em;
 color: #665544;}
 p.intro:first-line {
 font-weight: bold;}
 .credits {
 font-style: italic;
 text-align: right;}
 a {
 text-decoration: none;}
 a:hover {
 text-decoration: underline;}

 # Here are six rules you must always follow when giving a variable a name:

#  1 The name must begin with
 *a letter, dollar sign ($),or an*
*underscore (_). It must not start*
*with a number.*
# 4
*All variables are case sensitive,*
*so score and Score would be*
*different variable names, but*
*it is bad practice to create two*
*variables that have the same*
*name using different cases.*
# 2
*The name can contain letters,*
*numbers, dollar sign ($), or an*
*underscore (_). Note that you*
*must not use a dash(-) or a*
*period (.) in a variable name.*
# 5
*Use a name that describes the*
*kind of information that the*
*variable stores. For example,*
*fi rstName might be used to*
*store a person's first name,*
*l astNarne for their last name,*
*and age for their age.*
# 3
*You cannot use keywords or*
*reserved words. Keywords*
*are special words that tell the*
*interpreter to do something. For*
*example, var is a keyword used*
*to declare a variable. Reserved*
*words are ones that may be used*
*in a future version of JavaScript.*
*ONLINE EXTRA*
*View a full list of keywords and*
*reserved words in JavaScript.*
# 6
*If your variable name is made*
*up of more than one word, use a*
*capital letter for the first letter of*
*every word after the first word.*
*For example, f i rstName rather*
*than fi rstnarne (this is referred*
*to as camel case). You can also*
*use an underscore between each*
*word (you cannot use a dash)*