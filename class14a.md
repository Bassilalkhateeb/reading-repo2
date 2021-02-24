

### Transforms

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

### Transform Syntax

![image](images/Screenshot(182).png)


### 2D Transforms

- ### 2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. Later we will discuss how you can change this default point of rotation.

![image](images/Screenshot(184).png)


- ### 2D Scale

Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.



__*you can view all the proprieties [here](https://learn.shayhowe.com/advanced-html-css/css-transforms/)*__


### Transitions & Animations

- ### Transitions

As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

In the example below the box will change its background color over the course of 1 second in a linear fashion.

__* Transitions have many proprieties you can see full demos [here](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)*__


- ### Animations

Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

Animations Keyframes:
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

![image](images/Screenshot(186).png)

__*to see full demos and proprieties go [here](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)*__


[8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)

you can also check out these tricks and use it in your code:

[6 Buttons animated](https://codepen.io/retyui/pen/ByoaXV)
[CSS3 Animations: Keyframes](https://codepen.io/akshaychauhan/pen/oAfae)
[404](https://codepen.io/kieranfivestars/pen/MYdQxX)
[Pure CSS Bounce Animation](https://codepen.io/dp_lewis/pen/gCfBv)