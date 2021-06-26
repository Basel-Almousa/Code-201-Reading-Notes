# **JavaScript Object Literal**
A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.  
_The following demonstrates an example object literal:_  
var myObject = {  
    sProp: 'some string value',  
    numProp: 2,  
    bProp: false  
};

# Object Literal Syntax
Object literals are defined using the following syntax rules:  

+ A colon separates property name[1] from value.
+ A comma separates each name-value pair from the next.
+ A comma after the last name-value pair is optional.  
_If any of the syntax rules are broken, such as a missing comma or colon or curly brace, a JavaScript error will be triggered. Browser error messages are helpful in pointing out the general location of object literal syntax errors, but they will not necessarily be completely accurate in pointing out the nature of the error._
# Why and How We Use Object Literals
>+ Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.