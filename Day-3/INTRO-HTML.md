# INTRO-HTML

HTML stands for...who cares! When was the last time anybody couldn't solve a programming problem because they did not know what HTML stood for. Besides you did not sign up for this bootcamp to get a Computer Science education. You signed up for this bootcamp to learn enough coding to land your first developer job. And that is where the real learning starts anyways.

But anyways, back to HTML. You might still be wondering what DOES HTML actually stand for? It stands for Hyper Text Markup Language. The key here is Markup. What does it markup? Simple, text! Just text. It tells the browser what kind each piece of text on a page is. It structures the page. The best example/analogy I have ever read on HTML - I have read more than two - was in a book about HTML. Remember back in the day when we had newspapers?
It had blog posts printed on a weird type of paper, was kind of tall and left your fingers with a strange black residue.
Well anyways. The point I am trying to make is HTML would be the perfect language to organize and structure those articles on a page.

![Newspaper](https://raw.githubusercontent.com/Team-FCB/Assets/master/newspaper.png)

A newspaper is the ultimate HTML page! Don't worry if that doesn't make sense to you yet. It will in the future. I promise.

Alright, let's just look at a simple HTML document in it's pre-rendered form that is.

RAW HTML:
```
<!DOCTYPE html>  
<html>  
<head>  
	<title>Page Title</title>  
</head>  
<body>  
	<h1>My First Heading</h1>  
	<p>My first paragraph.</p>  
</body>  
</html>
```

 Let's look at the output/rendered form:

![html output](https://raw.githubusercontent.com/Team-FCB/Assets/master/simple_html.png)

## HTML Key Terms

 - Element
 - Tag
 - Attribute
 - Values
 - Parent Element
 - Child Element


 ![html element breakdown](https://raw.githubusercontent.com/Team-FCB/Assets/master/html_element.png)

 - source: tutorialrepublic.com

**Parent child example**:

    <div>
	    <h2>I am a child!</h2>
	    <p>So am I and I got a sister!</p>
    </div>

## Most Common Types of Elements:

### Document Structure

 - `<html></html>` Opens and closes an HTML document
 - `<head></head>` The first of two main sections of an HTML document.  The <head> section is used to provide information about the document for use primarily by search engines and browsers.
 - `<title></title>` The title of document. This element is nested inside the <head> section.  **In HTML5, this is the only required tag other than the DOCTYPE declaration.**
 - `<body></body>`The second of two main sections of an HTML document.
   The <body> section contains all the content of the web page.

### Common Text Structure Tags

 - `<h1> to <h6></h1>to</h6>` Headings. H1 is the main heading, H2 is
   secondary, etc.
 - `<p></p>`Paragraph
 - `<div></div>`A container for a  _block_  of content
 - `<span></span>`A container for  _in-line_  content, such as content inside a paragraph.
 - `<em></em>` Gives the contained text emphasis (usually as
   _italics_).
 - `<strong></strong>` Makes the contained text  **bold**.
 - `<a href = "document location"></a>`Link
 - `<ol></ol>`Ordered (numbered) list
 - `<ul></ul>`Unordered (bulleted) list
 - `<!-- -->`Comment. Anything between these tags is not displayed on the screen. This is useful for making notes to yourself or to others who may view the source code of the web page.
 - `<img>` Image tag!  Usually comes with src and alt attributes.

You can also provide a width and height attribute.

So for example:

    <img src="w3schools.jpg"  alt="W3Schools.com"  width="104"  height="142">

## Self Closing Tags?!
Not all elements are created equal! There are such thing as self closing elements. img elements are one of those. It makes sense if you think about it. Not everything needs content. In some instances the element is the content! Here are a few other self closing tags. You don't really have to memorize these. You will just start using them correctly and not even realize that you don't have to close them. Funny how that works.

-   `<br>`
-   `<embed>`
-   `<hr>`
-   `<img>`
-   `<input>`
-   `<link>`
-   `<meta>`
-   `<param>`
-   `<source>`
-   `<wbr>`

### Sources

 - https://learn.shayhowe.com/
