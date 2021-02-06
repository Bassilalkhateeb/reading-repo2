# Prework Reading Summary :

+ ## HTML Book :
### * Introduction which contains :
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
### +	HTML 4 : <!DOCTYPE html PUBLIC 
### +	HTML5: <!DOCTYPE html>
### +	The use of a DOCTYPE can also help the browser to render a page correctly.
### o	Comments in HTML : <!-- --> : If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters: <!-- comment goes here -->
### o	Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).


### o	Class Attribute: Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. For example, you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. Example : 
### +	"<p class="important">"
### o	Block Elements: Some elements will always appear to start on a new line in the browser window. These are known as block level elements. Example :
### +	<h1>, <p>, <ul>, and <li>
### o	Inline Elements: Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. Example :
### +	<a>, <b>, <em>, and <img>.
### o	Grouping Text & Elements In a Block (<div>): The <div> element allows you to group a set of elements together in one block-level box, a <div> element to contain comments from visitors.
### o	Grouping Text and Elements Inline (<span>): The <span> element acts like an inline equivalent of the <div> element. It is used to either:
### +	 Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
### +	2. Contain a number of inline elements.
### o	IFrames(<iframe>): An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame. One common use of iframes ) is to embed a Google Map into a page. The content of the iframe can be any html page (either located on the same server or anywhere else on the web).
### o	Escape Characters: There are some characters that are used in and reserved by HTML code.(For example, the left and right angled brackets.) Examples:
### +	If you want to include a copyright symbol on a web page you can use either &copy.
### +	When using escape characters, it is important to check the page in your browser to ensure that the correct symbol shows up. (Page 194 for more escape symbols).
### •	HTML5 Layout (Ch 17):
### o	The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
### o	The new elements provide clearer code (compared  with using multiple <div> elements). 
### o	Older browsers that do not understand HTML5 elements need to be told which elements are  block-level elements.
### o	 To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed.
### o	You can view the examples on pages( 445-448).
### •	Process and Design (Ch18):
### o	 Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.
### o	 After knowing your visitors Now that you know who your visitors are, you need to consider why they are coming. While some people will simply by a chance across your website, most will visit for a specific reason now you must know What Your Visitors are Trying to Achieve and What Information Your Visitors Need.
### o	 Site maps : Now that you know what needs to appear on your site, you can start to organize the information into sections or pages.The aim is to create a diagram of the pages that will be used to structure the site. This is known as a site map and it will show how those pages can be grouped.
### o	WireFrames
### o	A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
### o	Getting your message across using designThe primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.It’s important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.You can differentiate between pieces of information using size, color, and style. You can use grouping and similarity to help simplify the information you present.

### * So javascript is about making web pages more interactive and interesting, and user-friendly.
### what is a script ?
### * A script is a series of instructions that a computer can follow to achieve a goal.
### * You could compare scripts to any of the following:
+ ### RECIPES
+ ### HANDBOOKS
+ ### MANUALS
### * A script is made of instructions that computer can follow step by step
### * A script can run different section of the code depending on the situation around.
### * WRITING A SCRIPT:
 ### * To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
### * Start with the big picture of what you want to achieve, and break that down into smaller steps. 1: DEFINE THE GOAL First, you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve. 2: DESIGN THE SCRIPT To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart. You can then write down individual steps that the computer needs to perform in order to complete each individual task (and any information it needs to perform the task), rather like writing a recipe that it can follow. 3: CODE EACH STEP Each of the steps needs to be written in a programming language that the compu ter understands. In our case, this is JavaScript.
### * Designing a script tasks 
### * You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them.
### * DEFINING A GOAL & DESIGNING THE SCRIPT
### * The first thing you should do is detail your goals for the script (what you want it to achieve):
### * Next, break it into a series of tasks that have to be performed in order to achieve the goals:
### * SKETCHING OUT THE TASKS IN A FLOWCHART Often scripts will need to perform different tasks in different situations. You can use flowcharts to work out how the tasks fit together. The flowcharts show the paths between each step.
### * Arrows show how the script moves from one task to the next. The different shapes represent diff€rent types of tasks. In some places there are decisions which cause the code to follow different paths.


## * The conclusion :
### * A script is a series of instructions that the computer can follow in order to achieve a goal.
 ### * Each time the script runs, it might only use a subset of all the instructions. 
### * Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically. 
### * To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
### * EXPRESSIONS
### * An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.
### * 	EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
### * In order for a variable to be useful, it needs to be given a value. As you have seen, this is done using the assignment operator (the equals sign).
### * EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
### * You can perform operations on any number of individual values (see next page) to determine a single value.
### * OPERATORS
### * Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
### * ASSIGNMENT OPERATORS Assign a value to a variable
### * ARITHMETIC OPERATORS (+ , - , * ,++) Perform basic math
### * STRING OPERATORS Combine two strings (greeting= 'Hi 1 + 'Mol ly';) The value of greeting is now Hi Molly.
### * COMPARISON OPERATORS Compare two values and return true or false
### * LOGICAL OPERATORS Combine expressions and return true or false