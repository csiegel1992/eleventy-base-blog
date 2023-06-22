---
title: The Dom
description: Understanding the Document Object Model
date: 2023-06-08
tags: 
- The Dom 
- Events
- Preventing Defaults 
---


Understanding the anatomy of a website is crucial for web developers. In this session we explored the fundamental components that make up a website. From the structure provided by HTML to the presentation offered by CSS and the interactivity enabled by JavaScript by using the and maipulating The Dom.

#### HTML for Structure and CSS for Presentation:
The foundation of any website lies in its content. HTML (Hypertext Markup Language) serves as the structural backbone, defining the elements and layout of the web page. HTML tags create the framework for text, images, links, headings, paragraphs, and more. CSS (Cascading Style Sheets) complements HTML by providing the means to style and visually enhance the content. With CSS, you can specify colors, fonts, margins, borders, and other visual properties, creating an appealing and cohesive design.

#### IDs and Classes: 
In HTML and CSS, IDs and classes are used to target specific elements for styling or manipulation. An ID is denoted by the # prefix in CSS and must be unique, applying to only one element on a webpage. On the other hand, classes are denoted by the . prefix and can be shared by multiple elements, allowing you to style or modify a group of elements simultaneously. Understanding the distinction between IDs and classes is vital for effective website development and management.

#### Nesting Elements 
HTML elements nest inside one another, forming a hierarchical structure. For example, an anchor tag may be nested within a paragraph, which is nested within a main element, itself nested within the body, and ultimately inside the HTML element. This nesting hierarchy helps organize and structure the content of a webpage.

#### The DOM Tree: 
The Document Object Model (DOM) represents the HTML document as a tree structure. When a webpage is loaded, the browser constructs the DOM tree, which consists of interconnected nodes representing each element and its relationship to other elements. The DOM provides a programming interface that allows JavaScript to interact with the webpage's structure, enabling dynamic manipulation of content and interactivity.

#### Accessing the DOM:
JavaScript leverages the DOM to access and modify the content of a webpage. By utilizing the document object, which represents the loaded webpage, developers can dynamically change existing HTML elements, retrieve their values, or even create new elements from scratch. Accessing the DOM can be done using methods like getElementById, getElementsByTagName, getElementsByClassName, querySelector, and querySelectorAll.

#### Working with Events: 
Events are objects triggered by user actions on a webpage, such as clicks, mouse movements, key presses, and form submissions. JavaScript allows you to listen for these events and execute specific actions in response. By using event listeners and attaching functions to elements, you can create interactive and responsive websites. Common events include click, mouseover, mouseout, keyup, focus, blur, and submit.

#### Preventing Defaults and Event Propagation:
Elements like links and checkboxes have default behaviors determined by the browser. However, JavaScript provides a way to prevent these default behaviors by calling the event object's preventDefault() method. This feature allows developers to customize the functionality of elements and control how events propagate through nested elements.

#### Forms:
HTML forms serve as a means to collect user input, such as text, checkboxes, radio buttons, and more. JavaScript enables developers to retrieve the values entered in form elements, allowing for further processing and validation. By accessing the value property of form elements, you can gather user data and use it in your code.


###### Please find a link to the tasks completed in my codepen <a href="https://codepen.io/C-siegel31/pen/eYPMrBQ?editors=1111">here</a>.
