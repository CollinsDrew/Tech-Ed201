# How the **Web** works

The Web is known as a *client-server system*. Your computer is the *client* and the remote computers that store electronic files are the *servers*.
When you enter something like Google.com the request goes to one of many special computers on the Internet known as Domain Name Servers (DNS).
All of these requests are then routed through various routers and switches.
The domain name servers keep a table of machine names and their IP address'.
so when you type in Google.com it gets translated into a number, which identifies the computers that serve the Google Website to you.
When you want to view a web page, you must initiate the activity by requesting a page using your browser.
The browser then asks a domain name server to translate the domain name you requested into an IP address.
The browser then sends a request to that server for the page you want, using a standard called Hypertext Transfer Protocol (HTTP).
Information is sent around the world via fibre optic cables, the data is broken down into 6-bit '**packets**', and sent in binary code.
This binary code is then translated back in to its original code once all the **packets** have been recieved.
The browser then collects all of the information, and displays this to your computer in the form of Web page.

![web works](webworks.jpeg)

## **HTML** parsing

*Parsing* means taking the code we write as text (HTML, CSS, JS etc) and transform it into something that the browser can work with.
*Parsing* is done by the **browser engine**.
The **browser engine** is the core component of every major browser, and it's role is to combine all of the structure, such as **HTML**,
**CSS** and **Javascript**, and present the web page on to our screens.
**HTML** parsing involves 2 steps.
1. tokenization
2. tree construction

What results at the end of the tokenization process is a series of zero or more of the following tokens.
DOCTYPE, start tag (<tag>), end tag (</tag>), self-closing tag (<tag/>), attribute names, values, comments, characters, end-of-file or plain text content within an element.
After the first token gets created, tree building starts. This is essentially creating a tree like structure (called the Document Object Model) based on the previously parsed tokens. The DOM tree describes the content of the HTML content.

## **CSS** parsing

While the HTML content is being parsed, the **CSS** are depolyed. 
After loading the CSS files, the parsing of CSS occurs, similar to the parsing of the HTML files, but there’s a slight difference. The parsing of CSS files takes place in two steps, and it’s a bit more complex.
The first step is cascading and resolving any conflicts.
The second step is processing the final CSS values.

## **JS** parsing

While the CSS is being parsed and the CSSOM (CSS object model) created, other assets, including JavaScript files, are downloading (thanks to the preload scanner). JavaScript is interpreted, compiled, parsed and executed. The scripts are parsed into abstract syntax trees. Some browser engines take the Abstract Syntax Tree and pass it into an interpreter, outputting bytecode which is executed on the main thread. This is known as JavaScript compilation.

## How can you find images to add to a Website?

There are a couple of ways to add images to your website.
1. Copy the URL of the image you wish to insert. Open your index. html file and insert it into the img code, and then save the HTML file
2. Save the image to your local machine, upload the image and add to your add HTML file using img src

## What is the first step to designing a Website?

1. Visualise your goal
2. Determine your content
3. Determine your audience
4. Design a wireframe
