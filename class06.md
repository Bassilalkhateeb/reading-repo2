
## What is an Object ?

### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

- ### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES.
- ### IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS.

![image](images/Screenshot(83).png)


## Creating an Object :

1. ### Literal Notation : is the most popular and easiest way to create objects.

![image](images/Screenshot(85).png)


 - ### Accessing an Object and Dot Notation : you access the proprieties and methods of an object using dot notation, you can access also access proprieties using square brackets.

 ![image](images/Screenshot(87).png)



2. ### Constructor Notation : The new keyword and the object constructor creat a blank object, you can then add properties and methods to the object.

![image](images/Screenshot(89).png)



## Document Object Model :

The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.


### The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

- ### MAKING A MODEL OF THE HTM L PAGE
- ### ACCESSING AND CHANGING THE HTML PAGE 


### THE DOM TREE IS A MODEL OF A WEB PAGE : As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.


### Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser. 



### DOM TREE : 

![image](images/Screenshot(91).png)





### WORKING WITH THE DOM TREE:

Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.


### Catching DOM Queries :

![image](images/Screenshot(93).png)


![image](images/Screenshot(95).png)




### ACCESSING ELEMENTS :

DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 


Sometimes you will just want to access one
individual element (or a fragment of the page that
is stored within that one element). Other times you
may want to select a group of element s, for example,
every '<hl>' element in the page or every <1 i>
element within a particular list. 











