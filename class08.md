

# Ch 15 : Layouts :


## Key Concepts in Positioning Elements :

- ### CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
- ### Block-level elements : start on a new line '<h1> <p> <ul> <li>'.
- ### Inline elements : flow in between surrounding text '<img> <b> <i>'

- ### Containing Elements : If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- ### Controlling the Position of Elements :

 - ### Normal flow : 'position:static' In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: 'position: static;'.


 - ### Relative Positioning : 'position:relative' Relative positioning moves an element in relation to where it would have been in normal flow.


 - ### Absolute positioning: 'position:absolute' When the position property is given a value of absolute,the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.


 - ### Fixed Positioning : 'position:fixed' Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect. To control where the fixed position box appears in relation to the browser window, the box offset properties are used.

 - ### Overlapping Elements : 'z-index' When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.

  __*for more go to Duckett html book p 362-376*__









 - ### To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.)

- ## Screen Sizes : Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

- ## Screen Resolution : Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

- ### Page Sizes : Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).

- ## Fixed Width Layouts : Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
 __*Advantages and Disadvantages are on page 381*__



- ## Liquid Layouts : Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages. 
 __*Advantages and Disadvantages are on page 382*__

- ## Possible Layouts: 960 Pixel wide12 Column Grid

![image](/images/Screenshot (63).png)



- ## Multiple Style Sheets : There are two ways to add multiple style sheets to a page :

 1. ### Your HTML page can link to one style sheet and that stylesheet can use the '@import' rule to import other style sheets. 
 __*If a styesheet uses the @import rule, it should appear before the other rules.*__

 2. ###  In the HTML you can use a separate '<link>' element for each style sheet.


## Conclusion : 

- ### '<div>' elements are often used as containing elements to group together sections of a page.

- ### Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

- ### The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)

- ### Pages can be fixed width or liquid (stretchy) layouts.

- ### Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

- ### Grids help create professional and flexible designs.

- ### CSS Frameworks provide rules for common tasks.

- ### You can include multiple CSS files in one page.
