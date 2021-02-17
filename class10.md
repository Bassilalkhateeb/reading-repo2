
# Error Handling and Debugging :


### JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.


### ORDER OF EXECUTION :

To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

### EXECUTION CONTEXTS

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.


### The stack :

![image](images/Screenshot(137).png) ![image](images/Screenshot(140).png)



### UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.At that point, the interpreter stops and looks for exception-handling code.



### ERROR OBJECTS:

Error objects can help you find where your mistakes are and browsers have tools to help you read them.



### HOW TO DEAL WITH ERRORS

Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.

1.  DEBUG THE SCRIPT TO FIX ERRORS :If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.

You will find that the developer tools available in every major modern browser will help you with this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in Chrome are identical to those in Opera.)

2. HANDLE ERRORS GRACEFULLY : You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements. Sometimes, an error may occur in the script for a reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code.



### BROWSER DEV TOOLS & JAVASCRIPT CONSOLE:

The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

The JavaScript console is just one of several developer tools that are found in all modern browsers.

- #### HOW TO LOOK AT ERRORS IN CHROME :

The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

![image](images/Screenshot(142).png)


- #### WRITING FROM THE SCRIPT TO THE CONSOLE  :

You can also just type code into the console and it will show you a result.

Browsers that have a console have a console object, which has several methods that your script can use to display data in the console. The object is documented in the Console API.

![image](images/Screenshot(144).png)


### HANDLING EXCEPTIONS :

If you know your code might fail, use try, catch, and finally. Each one is given its own code block.

 - ### TRY : First, you specify the code that you think might throw an exception within the try block. If an exception occurs in this section of code, control is automatically passed to the corresponding catch block. The try clause must be used in this type of error handling code, and it should always have either a catch, finally, or both. If you use a continue, break, or return keyword inside a try, it will go to the finally option.

 - ### CATCH: If the try code block throws an exception, catch steps in with an alternative set of code. It has one parameter: the error object. Although it is optional, you are not handling the error if you do not catch an error. The ability to catch an error can be very helpful if there is an issue on a live website. It lets you tell users that something has gone wrong (rather than not informing them why the site stopped working).

 - ### FINALLY : The contents of the fi na 11 y code block will run either way - whether the try block succeeded or failed. It even runs if a return keyword is used in the try or catch block. It is sometimes used to clean up after the previous two clauses. You can nest checks inside each other (place another t ry inside a catch), but be aware that it can affect performance of a script.



### THROWING ERRORS :

If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them.

To create your own error, you use the following line: throw new Error( 'message' ) ; . This creates a new Error object (using the default Error object). The parameter is the message you want associated with the error. This message should be as descriptive as possible.



## Summary :

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
- Debugging is the process of finding errors. It involves a process of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.

__*You can find more details and examples in duckett JS book Ch10*__


