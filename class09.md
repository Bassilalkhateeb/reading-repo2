

# Forms:

### Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.


### Why Forms?

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

In addition to enabling users to search, forms also allow users to perform other functions online. You will see forms when registering as a member of a website, when shopping online, and when signing up for newsletters or mailing lists.

### Form Controls

There are several types of form controls that you can use to collect information from visitors to your site.

 - ### ADDING TEXT:
 1. Text input
 2. Password input
 3. Text area

 - ### Making Choices:

 1. Radio buttons
 2. Checkboxes
 3. Drop-down boxes

 - ### Submitting Forms:
 
 1. Submit buttons
 2. Image buttons

 - ### Uploading Files
 
 1. File upload



### How Forms Work

![image](images/Screenshot(119).png)


A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.


### Form Structure

- <form> : Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

- action : Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

- method : Forms can be sent using one of two methods: get or post.

 1. get : With the get method, the values from the form are added to the end of the URL specified in the action attribute.
 2. With the post method the values are sent in what are known as HTTP headers.

 3.  id : We look at the id attribute on page 183, but the value is used to identify the form distinctly from other elements on the page (and is often used by scripts — such as those that check you have entered information into fields that require values).


### Text Input :

- Input tag : The < input >  element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

- type="text" : When the type attribute has a value of text, it creates a single line text input.

- name : When users enter information into a form, the server needs to know which form control each piece of data was entered into. (For example, in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server.

- maxlength : You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. For example, if you were asking for a year, the maxlength attribute could have a value of 4.


### Summary :

- Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.

- Information from a form is sent in name/value pairs.

- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

- HTML5 introduces new form elements which make it easier for visitors to fill in forms.

__*you can read all about other form components in duckett HTML book p.144-175*__



# Lists, Tables and Forms

There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

### Bullet Point Styles:

The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 

It can be used on rules that apply to the <ol>, <ul>, and <li> elements.


### Images for Bullets:

You can specify an image to act as a bullet point using the list-style-image property.

The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.

This property can be used on rules that apply to the <ul> and <li> elements.


### Positioning the Marker:

Lists are indented into the page
by default and the list-style position property indicates whether the marker should appear on the inside or the outside of the box containing the main points.

This property can take one of two values:

- outside : The marker sits to the left of the block of text. (This is the default behavior if this property is not used.)

- inside : The marker sits inside the box of text (which is indented).


### List Shorthand:

As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called list-style, and it allows you to express the markers' style, image and position properties in any order.


### Table Properties :

You have already met several properties that are commonly used with tables. Here we will put them together in a single example using the following:

- width :to set the width of the table
- padding :to set the space between the border of each table cell and its content
- text-transform to convert the content of the table headers to uppercase
- letter-spacing, font-size :to add additional styling to the content of the table headers
- border-top, border-bottom : to set borders above and below the table headers 
- text-align : to align the writing to the left of some table cells and to the right of the others
- background-color to change the background color of the alternating table rows
- :hover to highlight a table row when a user's mouse goes over it.



### Border on Empty Cells :

If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown.

Since browsers treat empty cells in different ways, if you want to explicitly show or hide borders on any empty cells then you should use this property.

It can take one of three values:

- show :This shows the borders of any empty cells.

- hide :This hides the borders of any empty cells.

- inherit :If you have one table nested inside another, the inherit value instructs the table cells to obey the rules of the containing table.


### Gaps Between Cells:

The border-spacing property allows you to control the distance between adjacent cells. By default, browsers often leave a small gap between each table cell, so if you want to increase or decrease this space then the border-spacing property allows you to control the gap.

The value of this property is usually specified in pixels. You can specify two values if desired to specify separate numbers for horizontal and vertical spacing.

- collapse :Borders are collapsed into a single border where possible. (border-spacing will be ignored and cells pushed together, and empty-cells properties will be ignored.)

- separate :Borders are detached from each other. (border-spacing and empty-cells will be obeyed.)


__*more about the properties and examples in duckett book pages 330-357*__



### Web Developer Toolbar :

This helpful extension for Firefox and Chrome provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML.




## Summary :

- In addition to the CSS properties covered in other chapters which work with the contents of all elements,there are several others that are specifically used to control the appearance of lists, tables, and forms.

- List markers can be given different appearances using the list-style-type and list-style image properties.

- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.

- Forms are easier to use if the form controls are vertically aligned using CSS.

- Forms benefit from styles that make them feel more interactive.




# Events :

When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.


### DIFFERENT EVENT TYPES :

Here is a selection of the events that occur in the browser while you are browsing the web. Any of these events can be used to trigger a function in your JavaScript code.

![image](images/Screenshot(120).png)


### HOW EVENTS TRIGGER JAVASCRIPT CODE:

1. Select the element node(s) you want the script to respond to.
2. Indicate which event on the selected node(s) will trigger the response.
3. State the code you want to run when the event occurs. 

![image](images/Screenshot(122).png)


### THREE WAYS TO BIND AN EVENT TO AN ELEMENT :

Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers.

1. HTML EVENT HANDLERS : *This is bad practice, but you need to be aware of it because you may see it in older code.*

2. TRADITIONAL DOM EVENT HANDLERS : DOM event handlers were introduced in the original specification for the DOM. They are considered better than HTML event handlers because they let you separate the JavaScript from the HTML.

3. DOM LEVEL 2 EVENT LISTENERS : Event listeners were introduced in an update to the DOM specification (DOM level 2, released in the year 2000). They are now the favored way of handling events.


#### HTML EVENT HANDLER ATTRIBUTES (DO NOT USE) :

In the HTML, the first <input> element has an attribute called onb l ur (triggered when the user leaves the element). The value of the attribute is the name of the function that it should trigger.


#### TRADITIONAL DOM EVENT HANDLERS : 

All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.

![image](images/Screenshot(124).png)



#### EVENT LISTENERS :

Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers.

![image](images/Screenshot(126).png)


#### USING PARAMETERS WITH EVENT HANDLERS & LISTENERS :

Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround.

![image](images/Screenshot(128).png)


### Event Flow :

![image](images/Screenshot(131).png)

![image](images/Screenshot(132).png)


### THE EVENT OBJECT :

![image](images/Screenshot(134).png)


### EVENT DELEGATION :

Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.

If users can interact with a lot of elements on the page, such as:
- a lot of buttons in the UI
- a long list
- every cell of a table
adding event listeners to each element can use a lot of memory and slow down performance. Because events affect containing (or ancestor) elements (due to event flow - p260), you can place event handlers on a containing element and use the event object's target property to find which of its children the event happened on.

By attaching an event listener to a containing element, you are only responding to one element (rather than having an event handler for each child element).
You are delegating the job of the event listener to a parent of the elements.


### Where Events occurs ?

![image](images/Screenshot(136).png)




## Summary:

- Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).

- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

- When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.

- You can use event delegation to monitor for events that happen on all of the children of an element.

- The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.


__*for more examples and details please go to duckett JS book (pp.243-292)*__