# Class 6

## JavaScript Object Basics

JavaScript objects are containers for named values called properties. In JavaScript, almost "everything" is an object.
JavaScript defines 7 types of primitive data types:
- string
- number/integer
- boolean
- null
- undefined
- symbol
- bigint

Object literals allow you to assign properties, with values, to an object. This is usefull when you have objects that share the same properties, but have
different values.
Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value).
Arrays are a special type of variable that is also mutable and can also be used to store a list of values.
Dot notation is quicker to write and easier to read. Square bracket notation allows access to properties containing special characters and
selection of properties using variables.

## DOM

**DOM** stands for 'Doucument Object Model".
The Document Object Model (DOM) is an application programming interface (API) for HTML documents.
With the Document Object Model, programmers can build documents, navigate their structure, and add, modify, or delete elements and content.
Anything found in an HTML document can be accessed, changed, deleted, or added using the Document Object Model.
JavaScript allows you to manipulate the DOM that controls the client side scripting.
DOM is made up of the ***real DOM*** and the ***virtual DOM***.
The real DOM is the static page template. The Virtual DOM is a dynamic version of the template, acting as a mask for the ***real DOM***.
To avoid the entire page reloading client side the real DOM reloads in the background and the virtual DOM will only reload the parts that have changed. 
Javascript is what causes the changes to these parts when users interact with a website.
