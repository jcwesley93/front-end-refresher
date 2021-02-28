# What is CSS?

**CSS** is a language for specifying how documents are present to users - how they are styled, laid out, etc. 

CSS is a rule-based language - you define rules specifiying groups of styles that should be applied to particular elements or groups of elements on your web page.

**Creating a CSS File**

1. Create a file in the same folder as your HTML document, naming it "styles.css"
2. Link the CSS file in the `<head>` of the HTML document:  
`<link rel="stylesheet" href="styles.css">`.  

**Styling HTML Elements**

We can style elements using *element selector* - a selector that directly matches an HTML element name.  
`p { color: green; }`

`p, li { color: red; }`  

**Adding A Class** 
If you want to style a subset of the elements without changing the others, you can add a class to the HTML element. 

*HTML*
`<ul>`
  `<li>Item one</li>`

  `<li class="special">Item two</li>`

  `<li>Item <em>three</em></li>`
`</u;>`
 
 *CSS*
 `.special {
  color: orange;
  font-weight: bold;
}`
