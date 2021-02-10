

# Images :

### There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

### Choosing Images for Your Site : A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

### Storing Images on Your Site : If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

 - ### Adding Images: '<img>'....src....alt....title.

 - ### Height & Width of Images : height...width.

 - ### Where to Place Images in Your Code :
 1. ### 1: before a paragraph.
 2. ### 2: inside the start of a paragraph.
 3. ### 3: in the middle of a paragraph.


### Three Rules for Creating Images: There are three rules to remember when you are creating images for your website which are summarized below. We go into greater detail on each topic over the next nine pages.

 1. ### Save images in the right format.
 2. ### Save images at the right size.
 3. ### Use the correct resolution.



### Tools to Edit & Save Images:

- ### Image Dimensions : The images you use on your website should be saved at the same width and height that you want them to appear on the page.
- ### Cropping Images.
- ### Image Resolution: Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

- ### Vector Images : Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator.

- ### Animated GIFs: Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations.

- ### Transparency: Creating an image that is partially transparent (or "see-through") for the web involves selecting one of two formats:
 1. ### Transparent GIF
 2. ### PNG


### Examining Images on the Web : 
- ### Checking the Size of Images.
- ### Downloading Images.


### HTML5: Figure and Figure Caption :
 1. ### <figure> : Images often come with captions. HTML5 has introduced a new '<figure>' element to contain images and their caption so that the two are associated. You can have more than one image inside the <figure> element as long as they all share the same caption.

 2. ### <figcaption> : The <figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image. Before these elements were created there was no way to associate an <img> element with its caption.


## Conclusion :

- ### Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.
- ### You should save images at the size you will be using them on the web page and in the appropriate format.
- ### You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.



# Colors :

### Color can really bring your pages to life.


### Color : The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
 - ### rgb values These express colors in terms of how much red, green and blue are used to make it up For example: rgb(100,100,90)
 - ### hex codes These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80.
 - ### color names There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
### Background Color:
 - ### background-color : CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

### You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page). If you do not specify a background color, then the background is transparent. By default, most browser windows have a white background, but browser users can set a background color for their windows, so if you want to be sure that the background is white you can use the background-color property on the element.

### Understanding Colors:
- ### Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.


### Contrast
- ### When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible. (duckett book html and css page 253).


### CSS3: Opacity
- ### opacity, rgba : CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).



### CSS3: HSL Colors
- ### CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.
- ### hue Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.
- ### saturation Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.
- ### lightness Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.

### CSS3: HSL & HSLA
- ### hsl, hsla: The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for:
- #### hue This is expressed as an angle (between 0 and 360 degrees).
- #### saturation This is expressed as a percentage.
- #### lightness This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black.
- #### The hsla color property allows you to specify color properties using hue, saturation, and lightness as above, and adds a fourth value which represents transparency (just like the rgba property). The a stands for:
- #### alpha This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75 represents 75% transparency.


## Conclusion

- ### Color not only brings your site to life, but also helps convey the mood and evokes reactions.
- ### There are three ways to specify colors in CSS: RGB values, hex codes, and color names. 
- ### Color pickers can help you find the color you want. 
- ### It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- ### CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA. 
- ### CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.








# Text :


### The properties that allow you to control the appearance of text can be split into two groups:
- ### Those that directly affect the font and its appearance (including the typeface, whether it is regular, bold or italic, and the size of the text).
- ### Those that would have the same effect on text no matter what font you were using (including the color of text and the spacing between words and letters).


### Typeface Terminology:

 1. ### Serif : Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs.
 2. ### Sans-Serif : Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
 3. ### Monospace : Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

 ![image](images/Screenshot (64).png)


### Choosing a Typeface for your Website: When choosing a typeface, it is important to understand that a browser will usually only display it if it's installed on that user's computer.

### Type Scales : You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.
### Units of Type Size : 
 1. ### Pixels
 2. ### Percentages
 3. ### Ems


### Attribute Selectors : You met the most popular CSS selectors on page 238. There are also a set of attribute selectors that allow you to create rules that apply to elements that have an attribute with a specific value.


![image](images/Screenshot (66).png)





## Conclusion :

### You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.
### You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented. 
### If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
### There is a limited choice of fonts that you can assume most people will have installed.
### There are properties to control the choice of font, size, weight, style, and spacing.



__*For more go to Duckett HTML book pp.94-125 ,pp.246-263, and pp.264-299.*__






