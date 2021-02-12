
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


### Methods that select individual elements :

gitElementById() and querySelector(); can both search an entire document and return individual elements. Both use similar syntax.

![image](images/Screenshot(96).png)



## SELECTING AN ELEMENT FROM A NODELIST :
There are two ways to select an element from a Nodelist:
The item() method and array syntax.
Both require the index number of the element you want. 

1. THE item() METHOD :

 - ### Nodelists have a method
called item() which will return
an individual node from the
Node list. 

![image](images/Screenshot(98).png)



- ### Array Syntax : 

![image](images/Screenshot(100).png)


### Repeating actions for an entire  nodlist :


![image](images/Screenshot(102).png)


### TRAVERSING THE DOM : When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM. 

 - ### parentNode : This property finds the element node for the containing (or parent) element in the HTML

 - ### previousSibling nextSibling : These properties find the previous or next sibling of a node if there are siblings. 

 - ### firstChild lastChild : These properties find the first or last child of the current element.



### WHITESPACE NODES : Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.



### PREVIOUS & NEXT SIBLING, FIRST & LAST CHILD :

__*Examples in Duckett JS book page 210-211*__





### HOW TO GET/UPDATE ELEMENT CONTENT: So far this chapter has focused on finding elements in the DOM tree.The rest of this chapter shows how to access/update element content. Your choice of techniques depends upon what the element contains. 


### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE:

When you select a text node, you can retrieve or amend the content of it
using the node Va 1 ue property.


### ACCESSING & CHANGING A TEXT NODE: 

To work with text in an element, first the element node is accessed and then its text node.

The text node has a property called node Value which returns the text in that text node.

You can also use the node Value property to update the content of a text node.


### ACCESS & UPDATE TEXT WITH TEXT CONTENT (& INNER TEXT)  : The textContent property allows you to collect or update just the text that is in the containing element (and its children).




### ACCESSING TEXT ONLY : 

In order to demonstrate the difference between textContent and i nnerText, this example features a CSS rule to hide the contents of the '<em>' element.

The script starts off by getting the content of the first list item using both the textContent property and i nnerText. It then writes the values after the list. 


Finally, the value of the first list item is then updated to say sourdough bread. This is done using the textContent property.




### Adding or removing HTML content : There are two ways of doing that :

1. ### The inner Html Property :

![image](images/Screenshot(105).png)


2. ### DOM Manipulation methods :

![image](images/Screenshot(106).png)




### ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML: Using the innerHTML property, you can access and amend the contents of an element, including any child elements.


### ADDING ELEMENTS USING DOM MANIPULATION : 
 
 1. ### CREATE THE ELEMENT : 'createEl ement ()'

 2. ### GIVE IT CONTENT : 'createTextNode()'

 3. ### ADD IT TO THE DOM : 'appendChild()'



### ADDING AN ELEMENT TO THE DOM TREE : 

#### 'createElement ()' creates an element that can be added to the DOM tree, in this case an empty '<l i >' element for the list.

#### This new element is stored inside a variable called 'newEl' until it is attached to the DOM tree later on.

#### 'createTextNode()' allows you to create a new text node to attach to an element. It is stored in a variable called 'newText'.



### REMOVING ELEMENTS VIA DOM MANIPULATION : DOM manipulation can be used to remove elements from the DOM tree. 

1. ### STORE THE ELEMENT TO BE REMOVED IN A VARIABLE

2. ### STORE THE PARENT OF THAT ELEMENT IN A VARIABLE

3. ### REMOVE THE ELEMENT FROM ITS CONTAINING ELEMENT



### REMOVING AN ELEMENT FROM THE DOM TREE : 
This example uses the remove 'Chi1d ()' method to remove the fourth item from the list (along with its contents). 
The first variable, 'removeEl', stores the actual element you want to remove from the page (the fourth list item).
The second variable,
containerEl, stores the '<u 1 >' element that contains the element you want to remove.



### COMPARING TECHNIQUES: UPDATING HTML CONTENT :


In any programming language, there are often several ways to achieve the same task. In fact, if you asked ten programmers to write the same script, you may well find ten different approaches.

Some programmers can be rather opinionated and believe that their way is always the "right" way to do things - when there are often several right ways. If you understand why people prefer some approaches over others, then you are in a strong position to decide whether it meets the needs of your project.

### 'document.write()' : The document object's write () method is a simple way to add content that was not in the original source code to the page, but its use is rarely advised.


### Attribute Nodes : 

![image](images/Screenshot(107).png)



### CHECK FOR AN ATTRIBUTE AND GET ITS VALUES : 

Before you work with an attribute, it is good practice to check whether it exists. This will save resources if the attribute cannot be found.

The hasAttri bute() method of any element node lets you check if an attribute exists. The attribute name is given as an argument in the parentheses. 

Using hasAttribute() in an if statement like this means that the code inside the curly braces will run only if the attribute exists on the given element.


### CREATING ATTRIBUTES & CHANGING THEIR VALUES :

The className property allows you to change the value of the cl ass attribute. If the attribute does not exist, it will be created and given the specified value.

You have seen this property used throughout the chapter to update the status of the list items. Below, you can see another way to achieve the task.

The setAttribute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute.




### REMOVING ATTRIBUTES :

To remove an attribute from an element, first select the element,then call removeAttribute () . It has one parameter: the name of the attribute to remove.

Trying to remove an attribute that does not exist will not cause an error, but it is good practice to check for its existence before attempting to remove it. 



## Conclusion : 

### The browser represents the page using a DOM tree. 

### DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. 

### You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.

### Whenever a DOM query can return more than one node, it will always return a Node list.

### From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.

### An element node can contain multiple text nodes and child elements that are siblings of each other. 

### In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).

### Browsers offer tools for viewing the DOM tree .

__*For much more information and examples visit Duckett js book p 183-242*__




# Understanding The Problem Domain Is The Hardest Part Of Programming: 

### Why problem domains are hard ?

Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?that has a very similar pattern repeated on it and is double-sided? Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

- #### Figure out what the major components of the picture are
- #### Sort the pieces by color or component
- #### Put together all the border pieces
- #### Put together each component of the picture from the piles you created

This all breaks down when you don’t have a picture with clear components that you can identify.


The same thing happens when writing code.  Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.


### What can you do about it?

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- ### Make the problem domain easier
- ### Get better at understanding the problem domain

> You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

Games are really good at this.  Look at most games today and you’ll find that you start with a very small problem domain.  The first level is usually a tutorial that has a basic set of things you can do so that you don’t get overwhelmed.  But, as you advance through the levels, you usually find they get harder and introduce new concepts that build gradually on what you know, until you understand a pretty large problem domain.


The other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.  Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.  It is much more expensive and time consuming to do things over than it is to do them right the first time.  I learn this lesson the hard way time and time again



### Quick update on my new product

I’m still not ready to unveil exactly what I am building, but I do have an active mailing list where you can sign up to find out when I release the product I’m working on to help developers get better career opportunities and market themselves.

So many developers don’t realize how much of an impact marketing themselves and branding can have on their opportunities.  I’m hoping to help developers learn not only how valuable marketing and branding is, but how to do it most effectively.

If you are interested, please sign up. (I won’t spam you.) [link](https://simpleprogrammer.com/lp/simple-programmer-newsletter-lp/)

This article was written by  __*John Sonmez*__









