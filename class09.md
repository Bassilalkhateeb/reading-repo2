

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

- <input> : The <input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.

- type="text" : When the type attribute has a value of text, it creates a single line text input.

- name : When users enter information into a form, the server needs to know which form control each piece of data was entered into. (For example, in a login form, the server needs to know what has been entered as the username and what has been given as the password.) Therefore, each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server.

- maxlength : You can use the maxlength attribute to limit the number of characters a user may enter into the text field. Its value is the number of characters they may enter. For example, if you were asking for a year, the maxlength attribute could have a value of 4.


### Summary :

- Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.

- Information from a form is sent in name/value pairs.

- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

- HTML5 introduces new form elements which make it easier for visitors to fill in forms.

__*you can read all about other form components in duckett HTML book p.144-175*__


