### Introduction to HTML:

- The browser parses the HTML file first anf then sends requests back to the server for any CSS files and any JavaScript files it has found from `<script>` elements, and from those, then parses the CSS and JavaScript.
  
 - We can use the  `<img>` element to put images on a web page.

- For creating a string enclose it in single quote marks. 

- Numbers don't have quotes around them.

- A variable is a container for a value.

- Attributes contain extra information about the element that won't appear in the content.

- The anatomy of our element is:
The opening tag: This consists of the name of the element wrapped in opening and closing angle brackets. 
The content: This is the content of the element.
The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. 

- The `<section>` tag defines a section in a document. The `<article>` tag specifies independent, self-contained content.
  
- A typical website includes Links ,Paragraphs, Headings, Numbered and bulleted lists,Tables,Images etc.
  
- `<meta>` tags always go inside the `<head>` element, and are typically used to specify page description, keywords, author of the document.
  
 How to start to design a Website.
  
 - The first step to design a website is asking questios like What exactly do I want to accomplish? ,How will a website help me reach my goals?
What needs to be done, and in what order, to reach my goals?
  
 - The most important question to answer is "what excatly do I want to accomplish?
  
  Semantics
  
 - The `<h1>` element is a semantic element, which gives the text it wraps around the role of "a top level heading on your page." But span doesn't have a semantic value. That's why we should use an `<h1>` element over a <span> element to display a top level heading.
  
 - Some of the benefits from writing semantic markup are:

Search engines will consider its contents as important keywords to influence the page's search rankings.
Screen readers can use it as a signpost to help visually impaired users navigate a page
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming
  
  
  **Read class 2**
  
###Introduction to HTML
  
Why is it important to use semantic elements in our HTML?
Semantic are important as they give our content the correct meaning and appearance so that the browser knows how to display it correctly.

How many levels of headings are there in HTML?
There are 6 heading elements in HTML.
`<h1>` `<h2>` `<h3>` `<h4>` `<h5>` `<h6>`

`<sup>` refers to the superscript
`<sub>` refers to the subscript
They are used for dates, chemical formulae, and mathematical equations.

When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
The title attribute must be added to provide the full expansion of the term.
  
###CSS
  
What are ways we can apply CSS to our HTML?
We can apply CSS to HTML with an external stylesheet, with an internal stylesheet, and with inline styles.
  
Why should we avoid using inline styles?
It is the not very efficient to implement inline styles for maintenance. One styling change might require multiple edits within a single web page.
It also makes everything more difficult to read and understand. 

 What is representing the selector?  - h2
 Which components are considered properties? - color and padding
  
 ###JavaScript
  
 What data type is a sequence of text enclosed in single quote marks? 
 string data type
 
 List 4 types of JavaScript operators.
 Addition, subtraction, multiplication, strictly equal to, does-not-equal
  
 Describe a real world Problem you could solve with a Function.
 Function to calculate mean,mode,median
  
 ###Conditions
 An if statement checks a __ and if it evaluates to ___, then the code block will execute.
 - condition - true
  
 What is the use of an else if?
 If we have multiple conditions that we need to check then we use else if statement.
  
 List 3 different types of comparison operators.
 === strictly equal
 < less than
 > greater than
   
 What is the difference between the logical operator && and ||?
 The && operator only returns true when both conditons are true, while the || operator only returns false when both of its conditions are false.
   
 **Read class 03**
   
 **Learn HTML**
1. When should you use an unordered list in your HTML document?
   Unordered list is used for grouping items that do not have a specific numerical ordering, and their order in the list is meaningless.
   
2. How do you change the bullet style of unordered list items?
   We can use the style attribute to change the bullet style of unordered list.
   
3. When should you use an ordered list vs an unorder list in your HTML document?
  Unordered list is used to create a list of related items, in no particular order. Ordered list is used to create a list of related items, in a specific
  order.
   
4. Describe two ways you can change the numbers on list items provided by an ordered list?
   We can change the numbers on list items by changing the value attribute.
   
   **Learn CSS**
   
 1.Describe the CSS properties of margin and padding.

   The padding sits around the content as white space while the margin is the outermost layer, wrapping the content, padding, and border as whitespace     between this box and other elements.
   
 2.List and describe the four parts of an HTML elements box as referred to by the box model.
   There are different parts of a box — margin, border, padding, and content. 
  
   
   **Learn JS**
   
  1. What data types can you store inside of an Array?
   Array can store various data types — strings, numbers, objects, and even other arrays. 
   
  2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
    You can access an item inside an array that is itself inside another array by chaining two sets of square brackets together.
   
  3.List five shorthand operators for assignment in javascript and describe what they do.
    assignment x = 3 , addition assignment x+=3, subtraction assignment x-=3, multiplication assignment x*=3, division assignment x/=3
   
  4. Answer will be 10dog - If you combine number with a boolean value then it gets converted into zero.
   
  5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
      We can use conditional statement while calculating grade. for e.g. if the marks are under 35 then the grade will be "F". If they are between 35 and 50 then the grade will be "C" etc.
   
   6. Give an example of when a Loop is useful in JavaScript.
  We can use loop for various purposes. One example can be: if the input provided by the user is less than 10 then display the answer otherwise keep adding/subtracting numbers.
   
   
 ***Read class 04***
   
   ***Creating Hyperlinks***
   
   1. To create a basic link, we wrap text or other content inside what element?
      To create a basic link, we wrap text or other content inside `<a>`element.
   
   2. The href attribute contains what information?
      It contains the web address.
   
   3. What are some ways we can ensure links on our pages are accessible to all readers?
      One of the best accessibility aids a screen reader user can have is an excellent content structure with headings, paragraphs, lists, etc.
      You should use clear language that is not overly complex and doesn't use unnecessary jargon or slang terms.
      You should give meaningful text labels, give text alternatives.
   
  
   ***CSS Layout***
   
  1.What is meant by “normal flow”?
   Normal Flow is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is essentially a      set of things that are all working together and know about each other in your layout.
   
  2.What are a few differences between block-level and inline elements?
   Block elements always start from a new line. Inline elements never start from a new line.
   Block elements cover space from left to right as far as it can go. Inline elements only cover the space as bounded by the tags in the HTML element.
   
  3.___ positioning is the default for every html element.
   Static positoning is the default for every html element.
   
  4.Name a few advantages to using absolute positioning on an element.
   Absolute positioning takes elements out of the regular document flow while also affecting the layout of the other elements on the page.
   This is a very powerful type of positioning that allows you to place any page element exactly where you want it. 
   
   
  5.What is a key difference between fixed positioning and absolute positioning?
   Absolute positioning fixes an element in place relative to its nearest positioned ancestor. Fixed positioning elements are fixed with respect to the      viewport.
   
   
   ***Learn JS***
   
  1.Describe the difference between a function declaration and a function invocation.
   
    When we declared functions, they are not executed immediately. They are saved for later use, and will be executed later, when they are called upon which is known as invoking a function.
   
  2.What is the difference between a parameter and an argument?
   
    The values that are declared within a function when the function is called are known as an argument. Whereas, the variables that are defined when the     function is declared are known as a parameter.
   
   ***Pair programming***
   Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
   
   Engaged collaboration : With engaged collaboration the coding experience is more engaging and both programmers are more focused than if they were       working alone. 
   Job interview readiness : Pair programming will help you get ready for a job interview as it will improve your technical communication and confidence to explain your code.
   
   ***Read class 05***
   ***HTML Media***
   
1. What is a real world use case for the alt attribute being used in a website?
   Alt attributes enable screen readers to read the information about on-page images for the benefit of a person with complete lack of sight, visually impaired, or who is otherwise unable to view the images on the page. Alt text will be displayed in place of an image if an image file cannot load.
   (*https://moz.com/)
2. How can you improve accessibility of images in an HTML document?
   Add alt text which will help convey proper message to all users. Use Semantic HTML and use clear language.
3. Provide an example of when the figure element would be useful in an HTML document.
   It will be useful to organize your webpage.The figure tag is used to semantically organize the content of images, videos, audios or even charts or tables, block of codes in the HTML document.
4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
   Gif is a good choice for simple images and animations. SVG is ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes.
5. What image type would you use to display a screenshot on your website and why?
   I'll use lossless format for screenshots. This is particularly important if there's any text in your screenshot, as text easily becomes fuzzy and unclear under lossy compression.
   
   ***Learn CSS***
   
1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
   The color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color. 
2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
   Use background color and use different color for various texts on the webpage.
3. What should you consider when choosing fonts for an HTML document?
   You should use web safe fonts for your HTML document.
4. What do font-size, font-weight, and font-style do to HTML text elements?
   The size attribute specifies how large a font will be displayed in either relative or absolute terms. 
   The font-weight property sets how thick or thin characters in text should be displayed.
   The font-style property is mostly used to specify italic text. This property has three values: normal - The text is shown normally. italic,oblique 
5. Describe two ways you could add spacing around the characters displayed in an h1 element.
   We can use font-size and line-height.
   
   
   
   ###Read class 06 ###
   ###JavaScript Object Basics###

How would you describe an object to a non-technical friend you grew up with?
   
Generally, the meaning of an object will differ based on the type we use. e.g. he bought a car. Here, a car is an object.
In programming, the object has state, behavior, and identity. 
In programming, class is a template. It contains group of objects that has common properties. Now, Car becomes class(template) and all its related value are grouped as data member(variables) and member function(method).
*https://medium.com/
   
What are some advantages to creating object literals?
The advantage to creating object literals us that thet offer convenience, flexibility in declaration, and less code during declaration. 
   
How do objects differ from arrays?
Arrays are used to create and store data while object represents things with properties.
   
Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Bracket notation is that the bracket notation allows us to access object properties using variable or when the property's key is a number or includes a symbol or is two words with a space.
   
Evaluate the code below. What does the term this refer to and what is the advantage to using this?
 The this keyword refers to the current object the code is being written inside — so in this case this is equivalent to name and age."this" enables you to use the same method definition for every object you create.
   
   ###Introduction To The DOM###
What is the DOM?
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
   
Briefly describe the relationship between the DOM and JavaScript.
The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

   ### Things I want to know more about
  Learn website design in depth.
  Javascript OOP
  
  
  
  
  
