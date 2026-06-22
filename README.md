#   HTML Introduction
## What is HTML?
-   HTML stands for Hyper Text Markup Language.
-   HTML is the standard markup language for creating Web pages.
-   HTML describes the structure of a Web page.
-   HTML consists of a series of elements.
-   HTML elements tell the browser how to display the content.

## Explain HTML Work

-   The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document.
-   The `<html>` element is the root element of an HTML page.
-   The `<head>` element contains meta information about the HTML page.
-   The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
-   The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
-   The `<p>` element defines a paragraph.

## HTML Elements

**An HTML element is defined by a start tag, some content, and an end tag.**   
 The HTML element is everything from the start tag to the end tag:  
&emsp;&emsp;&emsp;`<tagname>`Content goes here...`</tagname>`   
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `1_Element.html`

## HTML Attributes
**HTML attributes provide additional information about HTML elements.**
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"    
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `2_Attribute.html`

## HTML Headings
**HTML headings are titles or subtitles that you want to display on a webpage.**    
HTML headings are defined with the `<h1> to <h6>` tags.     
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `3_Headings.html`

## HTML Paragraphs
**A paragraph always starts on a new line, and is usually a block of text.** 

- The HTML `<p>` element defines a paragraph.
- A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.     
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `4_Paragraphs.html`

## HTML Styles
**The HTML `style` attribute is used to add styles to an element, such as color, font, size, and more.**
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `5_Style.html`  

## HTML Text Formatting
**HTML contains several elements for defining text with a special meaning.**    
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `6_Formatting.html`

## HTML Comments
**HTML comments are not displayed in the browser, but they can help document your HTML source code.**   
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;`<!-- Write your comments here -->`     

## HTML Color
**HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.**     
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `7_Color.html`

## HTML Styles - CSS
- CSS stands for Cascading Style Sheets.
- CSS saves a lot of work. It can control the layout of multiple web pages all at once. 

**What is CSS?**    
Cascading Style Sheets (CSS) is used to format the layout of a webpage.

**Using CSS**   
CSS can be added to HTML documents in 3 ways:
- Inline - by using the `style` attribute inside HTML elements
- Internal - by using a `<style>` element in the <head> section
- External - by using a `<link>` element to link to an external CSS file

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `8_Style.html`

## HTML Links
**HTML Links - Syntax**     
The HTML `<a>` tag defines a hyperlink. It has the following syntax:    
`<a href="url">link text</a>`   

**HTML Links - The target Attribute**   
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link. 

The `target` attribute specifies where to open the linked document. 

The target attribute can have one of the following values:  

- `_self` - Default. Opens the document in the same window/tab as it was clicked  
- `_blank` - Opens the document in a new window or tab
- `_parent` - Opens the document in the parent frame
- `_top` - Opens the document in the full body of the window    
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `9_Links.html`

## HTML Image
Images can improve the design and the appearance of a web page.     
**HTML Images Syntax**      
The HTML `<img>` tag is used to embed an image in a web page. 

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image. 

The `<img>` tag has two required attributes:
- `alt` - Specifies an alternate text for the image
- `src` - Specifies the path to the image   
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `10_Images.html`

## HTML Tables
HTML tables allow web developers to arrange data into rows and columns.       
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex- `11_Tables.html`

## HTML Lists
HTML lists allow web developers to group a set of related items in lists    
**Unordered HTML list:**
- Item
- Item
- Item
- Item

**Ordered HTML list:**
1. First item
2. second item
3. Third item

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `12_Lists.html`

## HTML Block and Inline Elements
Every HTML element has a default display value, depending on what type of element it is.        
The two most common display values are block and inline.

**Block-level Elements**        
A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.       
A block-level element always takes up the full width available (stretches out to the left and right as far as it can).      
Two commonly used block elements are: `<p>` and `<div>`. 

**Here are the block-level elements in HTML:**
`<address>` `<article>` `<aside>` `<blockquote>` `<canvas>` `<dd>` `<div>` `<dl>` `<dt>` `<fieldset>` `<figcaption>` `<figure>` `<footer>` `<form>` `<h1>-<h6>` `<header>` `<hr>` `<li>` `<main>` `<nav>` `<noscript>` `<ol>` `<p>` `<pre>` `<section>` `<table>` `<tfoot>` `<ul>` `<video>`

**Inline Elements**     
An inline element does not start on a new line.     
An inline element only takes up as much width as necessary.     
This is a `<span>` element inside a paragraph. 

**Here are the inline elements in HTML:**       
`<a>` `<abbr>` `<acronym>` `<b>` `<bdo>` `<big>` `<br>` `<button>` `<cite>` `<code>` `<dfn>` `<em>` `<i>` `<img>` `<input>` `<kbd>` `<label>` `<map>` `<object>` `<output>` `<q>` `<samp>` `<script>` `<select>` `<small>` `<span>` `<strong>` `<sub>` `<sup>` `<textarea>` `<time>` `<tt>` `<var>`

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `13_Block_And_Inline_Elements.html`

## HTML class And id Attribute
The HTML `class` attribute is used to specify a class for an HTML element.    
Multiple HTML elements can share the same class.    

The HTML `id` attribute is used to specify a unique id for an HTML element.     
You cannot have more than one element with the same id in an HTML document.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `14_Class_And_Id_Attribute.html`

## HTML Buttons
Buttons let users interact with a web page. They can submit forms, run JavaScript, or trigger different actions when clicked.   
The HTML `<button>` element defines a clickable button.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `15_Buttons.html`

## HTML Iframes
An HTML iframe is used to display a web page within a web page.

**HTML Iframe Syntax**      
The HTML `<iframe>` tag specifies an inline frame.    
An inline frame is used to embed another document within the current HTML document.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `16_Iframes.html`

## HTML `<meta>` Element
The `<meta>` element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.     

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.      

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `17_Meta.html`

## HTML Layout Elements and Techniques
Websites often display content in multiple columns (like a magazine or a newspaper).

**HTML Layout Elements**    
HTML has several semantic elements that define the different parts of a web page:

![layout](/assets/layout.png)

- `<header>` - Defines a header for a document or a section.
- `<nav>` - Defines a set of navigation links.
- `<section>` - Defines a section in a document.
- `<article>` - Defines independent, self-contained content.
- `<aside>` - Defines content aside from the content (like a sidebar).
- `<footer>` - Defines a footer for a document or a section.
- `<details>` - Defines additional details that the user can open and close on demand.
- `<summary>` - Defines a heading for the `<details>` element.
- `<main>` - Specifies the main content of a document.
- `<figcaption>` - Defines a caption for a `<figure>` element.
- `<figure>` - Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
- `<mark>` - Defines marked/highlighted text.
- `<time>` - Defines a date/time.

**HTML Layout Techniques**      
There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:
- CSS frameworks
- CSS float property
- CSS flexbox
- CSS grid

## HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

**The `<form>` Element**    

The HTML `<form>` element is used to create an HTML form for user input:    
```
<form>
.
form elements
.
</form>
```
The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

**The `<input>` Element**  

The HTML `<input>` element is the most used form element.   
An `<input>` element can be displayed in many ways, depending on the type attribute.    

Here are the different input types you can use in HTML:     
`<input type="button">` `<input type="checkbox">` `<input type="color">` `<input type="date">` `<input type="datetime-local">` `<input type="email">`
`<input type="file">` `<input type="hidden">` `<input type="image">`
`<input type="month">` `<input type="number">` `<input type="password">`
`<input type="radio">` `<input type="range">` `<input type="reset">`
`<input type="search">` `<input type="submit">` `<input type="tel">`
`<input type="text">` `<input type="time">` `<input type="url">`
`<input type="week">`


&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Ex:- `18_Forms.html`
