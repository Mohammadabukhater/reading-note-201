# The <img> element is used to add images to a web page.
# You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
# You should save images at the size you will be using them on the web page and in the appropriate format.
# Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

# A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results

# <th>
**A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results**
# <thead>
*The headings of the table should sit inside the <thead> element.*
# <tbody>
*The body should sit inside the <tbody> element.*
# <tfoot>
*The footer belongs inside the <tfoot> element.*
**ex**

<html>
<head>
 <title>Tables</title>
</head>
<body>
 <table>
 <thead>
 <tr>
 <th></th>
 <th scope="col">Home starter hosting</th>
 <th scope="col">Premium business hosting</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <th scope="row">Disk space</th>
 <td>250mb</td>
 <td>1gb</td>
 </tr>
 <tr>
 <th scope="row">Bandwidth</th>
 <td>5gb per month</td>
 <td>50gb per month</td>
 </tr>
 <!-- more rows like the two above here -->
 </tbody>
 <tfoot>
 <tr>
 <td></td>
 <td colspan="2">Sign up now and save 10%!</td>
 </tr>
 </tfoot>
 </table>
</body>
</html>
# The <table> element is used to add tables to a web page.
# A table is drawn out row by row. Each row is created
with the <tr> element.
# Inside each row there are a number of cells
represented by the <td> element (or <th> if it is a
header).
# You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
# For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>

1
BROWSER OBJECT
MODEL
The Browser Object Model contains
objects that represent the current
browser window or tab. It contains
objects that model things like
browser history and the
device's screen. 
2
DOCUMENT OBJECT
MODEL
The Document Object Model uses
objects to create a representation of
the current page. It creates a new
object for each element (and each
individual section of text)
within the page. 
3
GLOBAL JAVASCRIPT
OBJECTS
The global JavaScript objects
represent things that the JavaScript
language needs to create a model
of. For example, there is an
object that deals only with
dates and times.