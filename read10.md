# Error Handling and Debugging
+ Errors, bugs, and therefore debugging are a part of life for a programmer. As the saying goes, if you haven’t made any mistakes, then you aren’t trying hard enough.
+ Dealing with errors actually involves two very different processes: error handling and debugging
+ Error handling is a combination of coding and methodology that allows your program to anticipate user and other errors. It allows you to create a robust program 
+ Error handling does not involve weeding out bugs and glitches in your source code, although some of the error handling techniques covered in this chapter can be used to great advantage at the debugging stage
# Debugging 
You’ve designed your solution and written the code. You start to load it into the browser with high hopes and excitement, only to be faced with an big ugly gray box telling you that the VBScript engine doesn’t like what you’ve done. So where do you start? Well, I find that another cup of coffee helps, but most of the time the error’s still there when I rerun the script.
+ Syntax errors  
You may have spelled something incorrectly or made some other typographical or syntactical error. When this happens, usually the program won’t run at all.
+ Logical errors  
Although syntactically correct, your program either doesn’t function as you expect, or it generates an error message.
# Logical errors that affect program results
+ This type of logical error can be quite hard to track down, because your program will execute from start to finish without failing, only to produce an incorrect result. There are an infinite number of reasons why this kind of problem can occur, but the cause can be as simple as adding two numbers together when you meant to subtract them. Because this is syntactically correct (how does the scripting engine know that you wanted “-” instead of “+”?), the script executes perfectly.
# The Microsoft Script Debugger
+ The Script Debugger has been designed to allow you to debug your scripts while they are running in the browser. You can trace the execution of your script and determine the value of variables during execution. The Script Debugger is freely downloadable from the Microsoft web site.  