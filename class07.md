

# Domain Modeling :

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.


### Model epic fails videos : 

Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.


Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.


### Generate random numbers :

To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.



### Summary:


Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

#### Here's some tips to follow when building your own domain models.

- ### When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- ### Model its attributes with a constructor function that defines and initializes properties.
- ### Model its behaviors with small methods that focus on doing one job well.
- ### Create instances using the new keyword followed by a call to a constructor function.
- ### Store the newly created object in a variable so you can access its properties and methods from outside.
- ### Use the this variable within methods so you can access the object's properties and methods from inside.













# HTML, Tables :


### What's a Table?

A table represents information in a grid format.Examples of tables include financial reports, TV schedules, and sports results.


### Basic Table Structure:

1. '<table>' : The <table> element is used to create a table. The contents of the table are written out row by row.

2. '<tr>' : You indicate the start of each row using the opening '<tr>' tag. (The tr stands for table row.) It is followed by one or more '<td>' elements (one for each cell in that row). At the end of the row you use a closing '</tr>' tag.

3. '<td>' : Each cell of a table is represented using a '<td>' element. (The td stands for table data.) At the end of each cell you use a closing '</td>' tag.


### Table Headings:

'<th>' : The '<th>' element is used just like the '<td>' element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

Even if a cell has no content, you should still use a '<td>' or '<th>' element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)


### Spanning Columns:

Sometimes you may need the entries in a table to stretch across more than one column.
The colspan attribute can be used on a '<th>' or '<td>' element and indicates how many columns that cell should run across.


### Spanning Rows:

You may also need entries in a table to stretch down across more than one row.
The rowspan attribute can be used on a '<th>' or '<td>' element to indicate how many rows a cell should span down the table.

### Long Tables:

There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).

1. '<thead>' : The headings of the table should sit inside the '<thead>' element.

2. '<tbody>' : The body should sit inside the '<tbody>' element.

3. '<tfoot>' : The footer belongs inside the '<tfoot>' element.



### Summary :

- ### The '<table>' element is used to add tables to a web page.

- ### A table is drawn out row by row. Each row is created with the '<tr>' element.

- ### Inside each row there are a number of cells represented by the '<td>' element (or '<th' if it is a header).

- ### You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

- ### For long tables you can split the table into a '<thead>', '<tbody>', and '<tfoot>'.






## Objects :

### Constructor Notation : The new keyword and the object constructor creat a blank object, you can then add properties and methods to the object.

![image](images/Screenshot(89).png)




### THIS (IT IS A KEYWORD) :

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.



### WHAT ARE BUILT-IN OBJECTS?

Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.


![images](images/Screenshot(108).png)





### THE BROWSER OBJECT MODEL: THE WINDOW OBJECT


The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.

![image](images/Screenshot(110).png)




### THE DOCUMENT OBJECT MODEL: THE DOCUMENT OBJECT:

The topmost object in the Document Object Model (or DOM) is the
document object. It represents the web page loaded into the current
browser window or tab. You meet its child objects in Chapter 5.


![image](images/Screenshot(111).png)



### GLOBAL OBJECTS: STRING OBJECT :

Whenever you have a value that is a string, you can use the properties
and methods of the String object on that value.

![image](images/Screenshot(112).png)


Each character in a string is automatically given a number, called an index
number. Index numbers always start at zero and not one (just like for
items in an array). 


### DATA TYPES REVISITED :

In JavaScript there are six data types:
Five of them are described as simple (or primitive) data types.
The sixth is the object (and is referred to as a complex data type).



### GLOBAL OBJECTS: NUMBER OBJECT:


Whenever you have a value that is a number, you can use the methods and properties of the Number object on it.


These methods are helpful when dealing with a range of applications from financial calculations to animations.

Many calculations involving currency (such as tax rates) will need to be rounded to a specific number of decimal places.



### GLOBAL OBJECTS: MATH OBJECT :

The Math object has properties and methods for mathematical constants and functions.


![image](images/Screenshot(114).png)



### Creating an instance of the date object :


![image](images/Screenshot(116).png)




### GLOBAL OBJECTS: DATE OBJECT (AND TIME) :


Once you have created a Date object, the following methods let you set
and retrieve the time and date that it represents.


![image](images/Screenshot(118).png)




## Conclusion :

### Arrays and objects can be used to create complex data sets (and both can contain the other).

### JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

### Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

### In an object, variables are known as properties of the object; functions are known as methods of the object.

### An object is a series of variables and functions that represent something from the world around you.

### Functions can take parameters (information required to do their job) and may return a value.

### Functions allow you to group a set of related statements together that represent a single task.

__*more details and formation in duckett js book p 106-144*__




