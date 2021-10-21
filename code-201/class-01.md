# Class 01

## HTML Chapter 1 Summary "Structure"
HTML is the backbone to every webpage. They are text documents that use things called elements/tags to create basic webpages that are readable by both humans and machines.

## Basic HTML Structure
```
<html>
    <body>
        <h1>This is the biggest text<h1>
        <p>This is more text</p>
    </body>
</html>
```

Above is the simple layout of a simple webpage.

### Two Vocabulary To Remember

- elements: Are the openning and closing tags along with the words that are between the angled brackets that tell the tags what they are going to do.
- tags: Are the two seperate parts of one element.

For instance ```<h1>``` is a tag. Whereas ```<h1></h1>``` is an element.

### Tags

The tags act like boxes that hold information that can be published on a webpage.

- opening tag: only has three things an two angle brackets <> and characters like p or h1.
- closing tag: has the same thing as an opening tag but has a / in front of the first character and after the left angled bracket.

### Attributes

Attributes can be added in-line within the tag elements to tell the machine what to do with that exact element.

Attributes consist of three things

1. Characters such as "id"
2. The "=" sign which sets a value to the characters
3. Next comes the open " with text or numbers inside followed by closing ".

For instance:

```
<p id="paragraphOne">Text inside here will display on the website<p>
```
Here you can see this attribute called "id" has been given an identifier you can call on later within your code.

Attributes can give HTML code more opportunities than jus the basic element and tags can.


## HTML Chapter 8 Summary "Extra Markup"
There can be extra markup made within your HTML. Some common extra markup things you will see are specifying the version of HTML you are using, how to identify and group elements, and how to comment and use meta information.

Since the World Wide Web was created there has been many versions of HMTL. We are currently using the HTML5 version.

### Doctypes
In order to create a site you need to tell the web browser what version your HTML is. You do this by declaring ```<!DOCTYPE html>``` at the top of your hmtl document, before your ```<html></html>``` tags.

### Comments in HTML
While you are coding you will need to be writing notes to yourself and other programmers who read your code. The way you do this is by creating comments.

```<-- this is a comment -->```

The best thing about comments is that they cannot be seen by anyone looking at the site on the World Wide Web. You can ony see them through your HTML document.

### ID Attribute
The ID attribute is a unique identifier that elements can use to differentiate itself from other elements that are the same.

For instance:

```
<p id="paragraphOne"><p/>
<p id="paragraphTwo"><p/>
```

This allows me when I am using my CSS to call the individual paragraphs in order to make each of them uniique to my specfications.

The id is a *global attribute* which means it can be used on any type of element.

### Class Attribute
Similar to the id attribute, the class attribute allows you to identify elements in a similar way. The only difference is the class elements group multiple elements together instead of make each and every single one unique.

For instance:

```
<p class="classified"></p>
<p class="extra classified"></p>
```

These class elements will not affect your code in any way besides give you another option to call on when formatting for CSS.

### Meta
The ```<meta>``` element **MUST** be in the ```<head>``` element. It allows the information on the webpage to be read by Google and other browsers to help in search and organization.

## HMTL Chapter 17 Summary "HTML5 Layout"
HTML5 is still being worked on today. It is constantly coming out with new elements/tags in order to help web developers create better webpages for the world.

### What do the new elements do?

1. They help indicate the structure and purpose of the web page
2. They help provide a clearer way to write code for the developer
3. Older browsers who cannot read HTML5 elements have to be told what elelemts are block-level elements.

## HTML Chapter 18 Summary "Process & Design"
When creating a website you don't just throw code on an HTML document and it turns out pretty. You need to have an outline or wireframe to do it.

### Important Steps to Designing a Website

1. Know who your audience is and cater to what their needs are and why they are coming to your site.
2. Create a sitemap or wireframe in order to visually structure and see what the site will look like.
3. Differentiate between different parts of your site by using borders, size, color, and images.
4. Use grouping in order to help you create a visually pleasing layout and a congruent flow of text and ideas.



[Home](README.md)