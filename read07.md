# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.
# Model epic fails videos
Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.



As you read this article, type out and run all code samples you come across. Do not copy and paste. Writing out and testing your code will help you remember how to implement domain models in JavaScript later.
# HTML Tables
HTML tables allow web developers to arrange data into rows and columns.

# Define an HTML Table
The \<table> tag defines an HTML table.

Each table row is defined with a \<tr> tag. Each table header is defined with a \<th> tag. Each table data/cell is defined with a \<td> tag.

By default, the text in \<th> elements are bold and centered.

By default, the text in \<td> elements are regular and left-aligned.  
+ **Note: The <td> elements are the data containers of the table.
They can contain all sorts of HTML elements; text, images, lists, other tables, etc.**
# HTML Table - Add a Border
to add a border to a table, use the CSS border property:  

+ Example  
table, th, td {  
  border: 1px solid black;  
}  
# HTML Table - Collapsed Borders
To let the borders collapse into one border, add the CSS border-collapse property:  

+ Example  
table, th, td {  
  border: 1px solid black;  
  border-collapse: collapse;  
}  
# HTML Table - Add Cell Padding
Cell padding specifies the space between the cell content and its borders.  

If you do not specify a padding, the table cells will be displayed without padding.  

To set the padding, use the CSS padding property:  

+ Example  
th, td {  
  padding: 15px;  
}  
# HTML Table - Left-align Headings
By default, table headings are bold and centered.  

To left-align the table headings, use the CSS text-align property:  

+ Example  
th {  
  text-align: left;  
}  
# HTML Table - Add Border Spacing
Border spacing specifies the space between the cells.  

To set the border spacing for a table, use the CSS   border-spacing property:  
  
+ Example  
table {  
  border-spacing: 5px;  
}  
# JavaScript Methods
JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition.
# Accessing Object Methods
You access an object method with the following syntax:  

_objectName.methodName()_
You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().  

This example accesses the fullName() method of a person object:  

+ Example  
name = person.fullName();  