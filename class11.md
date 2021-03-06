
# Images

### Controlling sizes of images in CSS:

You can control the size of an image using the width and height properties in CSS, just like you can for any other box Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

First you need to determine the sizes of images that will be used commonly throughout the site, then give each size a name. For example:
- small
- medium
- large

Where the < img > elements appear in the HTML, rather than using width and height attributes you can use these names as values for the class attribute. In the CSS, you add selectors for each of the class names, then use the CSS width and height properties to control the image dimensions.


### AligNing images Using CSS :

Rather than using the < img > element's align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved: 

1. The float property is added to the class that was created to represent the size of the image (such as the small class in our example).
2. New classes are created with names such as align-left or align-right to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.


### Centering images Using CSS: 

By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a block level element using the display property with a value of block. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

1. On the containing element, you can use the text-align property with a value of center.
2. On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.

You can specify class names that allow any element to be centered, in the same way that you can for the dimensions or alignment of images.


### Background Images:


The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box. If you search online, you will find lots of resources that offer background textures that you can use on your pages.


### Repeating Images:

The background-repeat property can have four values:

1. repeat :The background image is repeated both horizontally and vertically (the default way it is shown if the background-repeat property isn't used).
2. repeat-x :The image is repeated horizontally only (as shown in the first example on the left).
3. repeat-y :The image is repeated vertically only.
4. no-repeat :The image is only shown once.

The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:

1. fixed :The background image stays in the same position on the page.
2. scroll :The background image moves up and down as the user scrolls up and down the page.



### Background Position: 

When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed.
This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.


### Contrast of background images:

If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

![image](images/Screenshot(157).png)




## Summary:

- You can specify the dimensions of images using CSS.This is very helpful when you use the same sized images on several pages of your site.
- Images can be aligned both horizontally and vertically using CSS.
- You can use a background image behind the box created by any element on a page.
- Background images can appear just once or be repeated across the background of the box.
- You can create image rollover effects by moving the background position of an image.
- To reduce the number of images your browser has to load, you can create image sprites.







# Practical Information:

### Search Engine Optimization (SEO):

SEO is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines.

1. The Basics: Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers. At the heart of SEO is the idea of
working out which terms people are likely to enter into a search engine to find your site and then using these terms in the right places on your site to increase the chances that search engines will show a link to your site in their results.

2. On-Page Techniques : On-page techniques are the methods you can use on your web pages to improve their rating in search engines. The main component of this is looking at keywords that people are likely to enter into a search engine if they wanted to find your site, and then including these in the text and HTML code for your site in order to help the search engines know that your site covers these topics.

3. Off-Page Techniques : Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours. They are particularly interested in sites whose content is related to yours. For example, if you were running a website that sold fish bait, then a link from a hairdresser is not likely to be considered as relevant as one from an angling community. Search engines also look at the
words between the opening < a > tag and closing < /a> tag in the link. If the text in the link contains keywords (rather than just click here or your website address) it may be considered more relevant.


__*For more information please visit duckett html book (pp 476-492) & (pp 406-427)*__




# Flash, Video & Audio:

### How Flash Works?

Since the late 1990s, Flash has been a very popular tool for creating animations, and later for playing audio and video in websites.

Whether you are creating an animation or a media player in Flash, the files you put on your website are referred to as Flash movies. If you want to create your own Flash movie, you need to purchase the Flash authoring environment from Adobe. There are, however, several
companies that offer Flash animations and slideshows, as well as video and audio players that you can use without purchasing this tool. When you create a Flash file in the Flash authoring environment, it is saved with the .fla file extension. In order to use this file on a web page it has to be saved in a different format known as SWF. (It has the .swf file extension.). When you export the movie
into SWF format, Flash creates code that you can use to embed the Flash movie in your page. Traditionally, this code used the HTML < object> and < embed> tags. However, now it is more common to use JavaScript. To view Flash, browsers need to use a plugin (an extra piece of software that runs in the browser) called the Flash Player. Statistics commonly indicate that 98% of browsers on desktop computers have the Flash plugin installed. (The percentage of mobiles and tablets with it is much less.).



### Use of Flash:


Since 2005, a number of factors have meant that fewer websites are written in Flash or even use elements of Flash in their pages.

Despite this, Flash does have a future on the web because there are some things it does very well, such as creating animations. There are several reasons why fewer websites are using Flash these days, including: In 2005-6, a set of JavaScript libraries were launched (including Prototype, script.aculo.us, and JQuery) which made it easier for people to create animated effects using JavaScript. When Apple launched the iPhone in 2007 and later the the iPad in 2010, they took the decision not to support Flash. There have been laws introduced to ensure that websites are usable by those with visual or physical impairments — and Flash has been criticized because Flash content does not always meet accessibility requirements.

![image](images/Screenshot(160).png)
![image](images/Screenshot(161).png)






You can also read about video and images in html [Here](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)