# Reading Summary :

+ ## HTML Book :
### •	Introduction which contains :
### o	Talk s about how the book was made and the sections of the book (Html , Css , and the practical), then went to talking about how people access the web, and how websites are created.
### o	How the Web Works : Page (9-10) show you how the process goes when someone requests to visit a website even if they were in a different places.
### •	Structure (Ch 1) :
### o	 First it talks about how structuring of pages are important and the similarity between a word doc and a web page view (heading types and paragraphs.
### o	HTML code: “is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags”
### o	Tags: Tags act like containers. They tell you something about the information that lies between their opening and closing tags. (Page 22-23 show a description of some tags and a closer look to the structure of a tag).
### o	Attributes: Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.(Page 25-26)
### o	<head> , <body> , and <title> tags and how they are written in html file and what they should contain.
### •	Extra Mark-up (Ch 8):
### o	HTML Evolution: HTML 4 Released 1997, XHTML 1.0 Released 2000, HTML5 Released 2000.
### o	DOCTYPE : Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using; Examples : 
### 	HTML 4 : <!DOCTYPE html PUBLIC 
### 	HTML5: <!DOCTYPE html>
### 	The use of a DOCTYPE can also help the browser to render a page correctly.
### o	Comments in HTML : <!-- --> : If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters: <!-- comment goes here -->
### o	Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).


### o	Class Attribute: Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. For example, you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. Example : 
### 	<p class="important">
### o	Block Elements: Some elements will always appear to start on a new line in the browser window. These are known as block level elements. Example :
### 	<h1>, <p>, <ul>, and <li>
### o	Inline Elements: Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. Example :
### 	<a>, <b>, <em>, and <img>.
### o	Grouping Text & Elements In a Block (<div>): The <div> element allows you to group a set of elements together in one block-level box, a <div> element to contain comments from visitors.
### o	Grouping Text and Elements Inline (<span>): The <span> element acts like an inline equivalent of the <div> element. It is used to either:
### 	 Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
### 	2. Contain a number of inline elements.
### o	IFrames(<iframe>): An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame. One common use of iframes ) is to embed a Google Map into a page. The content of the iframe can be any html page (either located on the same server or anywhere else on the web).
### o	Escape Characters: There are some characters that are used in and reserved by HTML code.
