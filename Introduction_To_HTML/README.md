
# Introduction to HTML

## What is HTML?

* HTML (HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit.
* It can be as complicated or as simple as the web developer wants it to be. 
* HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way.

## Anatomy of an HTML elements

* The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. 
* The content: This is the content of the element. In this example, it is the paragraph text.
* The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends.

``` <p> Here is the content </p> ```

## Nesting elements

* Elements can be placed within other elements. This is called nesting. 
* Example: 

If we wanted to state that our cat is very grumpy, we could wrap the word very in a <strong> element, which means that the word is to have strong(er) text formatting:

``` <p>My cat is <strong>very</strong> grumpy</p> ```

The following is an example of the wrong way to do nesting

``` <p>My cat is <strong>very grumpy.</p></strong> ```

## Void elements

* Some elements consist of a single tag, which is typically used to insert/embed something in the document. Such elements are called void elements
* Example: 

``` <img
  src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png"
  alt="Firefox icon" />
```

## Attributes

Attributes contain extra information about the element that won't appear in the content.

An attribute should have:

* A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
* The attribute name, followed by an equal sign.
* An attribute value, wrapped with opening and closing quote marks.

## Boolean Attributes

* Sometimes you will see attributes written without values. This is entirely acceptable. These are called Boolean attributes.
* Boolean attributes can only have one value, which is generally the same as the attribute name. 
* Example:

``` 
<!-- using the disabled attribute prevents the end user from entering text into the input box -->
<input type="text" disabled />

<!-- text input is allowed, as it doesn't contain the disabled attribute -->
<input type="text" />
```
## Omitting quotes around attribute value

* If you look at code for a lot of other sites, you might come across a number of strange markup styles, including attribute values without quotes.
* This is permitted in certain circumstances, but it can also break your markup in other circumstances.
* Example:

``` <a href=https://www.mozilla.org/>favorite website</a> ```

The element in the code snippet above, <a>, is called an anchor. Anchors enclose text and turn them into links. The href attribute specifies the web address the link points to.

Anchors can also have a title attribute, a description of the linked page. However, as soon as we add the title in the same fashion as the href attribute there are problems:

``` <a href=https://www.mozilla.org/ title=The Mozilla homepage>favorite website</a> ```

## Anatomy of HMTL Document

``` <!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```
## Special Charaters in HTML

* In HTML, the characters <, >,",', and & are special characters. They are parts of the HTML syntax itself.  
* You can include special charaters in the code as shown in "GettingstartedwithHTML.html" File.       

## HTML Comments

* HTML has a mechanism to write comments in the code. 
* Browsers ignore comments, effectively making comments invisible to the user. 
* The purpose of comments is to allow you to include notes in the code to explain your logic or coding. 
* Example:

``` 
<p>I'm not inside a comment</p>

<!-- <p>I am!</p> --> 

```









