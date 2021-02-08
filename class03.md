
# HTML
## Lists :

## There are lots of occasions when we need to use lists. HTML provides us with three different types:

- ### Ordered lists : The ordered list is created with the '<ol>' element. Each item in the list is placed between an opening '<li>' tag and a closing '</li>' tag.

- ### Unordered lists : The unordered list is created with the '<ul>' element. Each item in the list is placed between an opening '<li>' tag and a closing '</li>' tag. 

- ### Definition lists : The definition list is created with the '<dl>' element and usually consists of a series of terms and their definitions. Inside the <dl> element you will usually see pairs of '<dt>' and '<dd>' elements.
  - ### '<dt>' This is used to contain the term being defined (the definition term).
  - ### '<dd>' This is used to contain the definition.

## Nested Lists :

### You can put a second list inside an '<li>' element to create a sublist or nested list.

## Conclusion :

- ### Ordered lists use numbers.
- ### Unordered lists use bullets.
- ### Definition lists are used to define terminology.
- ### Lists can be nested inside one another.


# Css 
## Boxes :

## Box Dimensions : By default a box is sized just big enough to hold its contents.

- ### To set your own dimensions for a box you can use the height and width properties. The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.

- ### When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.

- ### When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.

## Limiting Width : Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

## Limiting Height :
- ### The example on this page demonstrates these properties in action. It also shows you what happens when the content of the box takes up more space than the size specified for the box. 

## Overflowing content : The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

- ### hidden :This property simply hides any extra content that does not fit in the box.

- ### scroll : This property adds a scrollbar to the box so that users can scroll to see the missing content.

## Border, Margin & Padding : Every box has three available properties that can be adjusted to control its appearance:

- ### Border : Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

- ### Margin : Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

- ### Padding : Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.



![image](images/Screenshot(56).png)


## White space & Vertical Margin :

![image](images/Screenshot(57).png)


## Border Width :

### The border-width property is used to control the width of a border. The value of this property can either be given in pixels or using one of the following values :

- ### thin
- ### medium
- ### thick

## (You cannot use percentages with this property.)


## Border style : You can control the style of a border using the border-style property. This property can take the following values:

- ### solid
- ### dotted
- ### dashed
- ### double
- ### groove
- ### ridge
- ### inset
- ### outset
- ### hidden / none


## Border color : You can specify the color of a border using either RGB values, hex codes or CSS color names (as you saw on pages 251-252).

## Shorthand border :  The border property allows you to specify the width, style and color of a border in one property (and the values should be coded in that specific order).

## Padding : The padding property allows you to specify how much space should appear between the content of an element and its border.

## Margin : The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems.

## Centering Content : If you want to center a box on the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto. In order to center a box on the page, you need to set a width for the box (otherwise it will take up the full width of the page). Once you have specified the width of the box, setting the left and right margins to auto will make the browser put an equal gap on each side of the box. This centers the box on the page (or within the element that the box sits inside).

__*For more visit duckett html and css book p 300-329*__


## Conclusion :

- ### CSS treats each HTML element as if it has its own box. 
- ### You can use CSS to control the dimensions of a box.
- ### You can also control the borders, margin and padding for each box with CSS.
- ### It is possible to hide elements using the display and visibility properties.
- ### Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
- ### Legibility can be improved by controlling the width of boxes containing text and the leading.
 ### CSS3 has introduced the ability to create image borders and rounded borders.





 # JS

## ARRAYS :

* #### An array is a special type of variable. It doesn't just store one value; it stores a list of values.
* #### You should consider using an array whenever you are working with a list or a set of values that are related to each other.
* #### CREATING AN ARRAY : 
#### var colors;
1. #### colors ['white', 'black', ' custom'];
2. #### var colors = new Array('white ','black','custom');

* ### VALUES IN ARRAYS : Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).(more about arrays on page 72).


## SWITCH STATEMENTS :

- ### A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

###    switch (level) {
### case 'One ':
### title= 'Level 1 ' ;
### break; }



## Loops :

###  Loops check a condition , if it returns true , a code block will run , then the condition will be checked again , and if it still returns true the code block will run again, still repeats until the condition returns false. 


- ### For : 
 - ### Loop Counters : 

 ### For loops uses a counter as a condition, this instructs the code to run specified numbers of time, the condition is made up of three statements : 
  - ### Initializing
  - ### Condition
  - ### Update



- ### While :

``` var i = l ;
var msg = ' ' ;
II Set counter to 1 II Message II Store 5 times table in a variable while (i < 10) { msg += i + ' x 5 = ' + (i * 5) + ''; i++; 
document .getElementByid( ' answer') . innerHTML = msg;
```


#### This loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run. 
 
 
 
- ### Inside the code block there are two statements: 

 - ### The first statement uses the '+' operator, which is used to add new content to the msg variable. Each time the loop runs, a new calculation and line break is added to the end of the message being stored in it. So+" works as a shorthand for writing: msg = msg + 'new msg' (See bottom of the next page for a breakdown of this statement.)

 - ### The second statement increments the counter variable by one. (This is done inside the loop rather than with the condition.)
 
### When the loop has finished, the interpreter goes to the next line of code, which writes the msg variable to the page.

### 1*5=5 2*5=10 3*5=15 . ...(until) 9*5=45 In this example, the condition specifies that the code should run nine times. A more typical use of a while loop would be when you do not know how many times you want the code to run. It should continue to run as long as a condition is met.

__*For more visit Duckett JS book p 162-182*__


