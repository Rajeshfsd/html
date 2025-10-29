HTML
Basics
-	How Website works?
-	HTML Document Structure
-	HTML Tas and Elements
-	HTML Headings
-	HTML Paragraphs
-	HTML Comments
-	Text Formatting in HTML
-	Links and Anchors
-	Images in HTML
-	Void Elements in HTML
-	Lists in HTML
-	Tables in HTML
Advanced
-	HTML Map & Area Elements
-	HTML IFRAMES
HTML Picture Tag
-	HTML Figure Tag
-	HTML Audio Tag
-	HTML Video Tag
-	Forms and Input Elements
-	HTML Semantic Elements
-	HTML Meta Tags
-	HTML SEO
-	Website Ranking Score
-	Host Website Live for Free & Paid
======================================================================
How Website Works?
We have searched www.ndtv.com in our browser then what happens? A request is send to the server then server checks in database whether that domain exists or not. If that domain is present and got necessary files then those files as a response send to our browser and display as a website in our browser.
But what are those files that server send to our browser which displays that awesome website?
Those files are html, css, javascript files which are shared by server to our browser
So what is HTML?
HTML provides the structure and content of a webpage.
What is CSS?
CSS Styles and designs the appearance of the webpage
What is JavaScript?
Adds interactivity and dynamic behaviour to the webpage.

====
HTML is your structure. Css styles that structure and javascript adds interactivity to that.
====
HTML – HyperTest Markup Language
<p> HyperText is text which contains links to other texts </p>
<p> Markup Lang. It’s a way to give instructions to a computer about how content should be organized and displayed. </p>
<p> This is a <strong>bold</strong> text. </p>
Hypertext is text which contains links to other texts. The term was coined by Ted Nelson around 1965.
HyperMedia is a term used for hypertext which is not constrained to be text: it can include graphics, video and sound, for example. Apparently Ted Nelson was the first to use this term too.
Hypertext and HyperMedia are concepts, not products.
Hypertext can also be called as Hyperlinks.
History of HTML:
Early Beginnings(1980s):
The concept of hypertext was proposed by computer scientist Ted Nelson in the 1960s. In the 1980s, Tim Berners-Lee, a British computer scientist, introduced the World Wide Web(WWW) and developed the first HTML.
World Wide Web
World First Website using HTML only.
HTML 2.0(1995),
HTML 3.2(1997)
HTML 4.0(1997-1999)
HTML4 introduced significant improvements, including better support for forms, scripts, and style sheets. It was a crucial step toward modern web development.

HTML5 (2014): HTML5 was a major milestone, with a focus on multimedia, improved semantics, and better support for web applications. It introduced new elements like <video>, <audio>, and <picture>. HTML5 made web development more versatile and capable.
 
HTML SYNTAX:
<h1> Best HTML Course</h1>
 
why index.html?
<p> The File extension must be .html or .html </p>
<p> MS-DOS and Windows 3.1, had limitations on the number of characters in a filename. </p>
.ext	.txt	.doc	.bat	.com	.zip
At first only 3 letters are supported for describing extensions
<p> The file name must be the index.html because it’s a default path of our homepage or the root of our website. </p>
<!DOCTYPE html>  Let the browser know it’s an HTML5. Appear once, at the top of the page
<html>  Root of an HTML Document (inside this we have to write our data or code)
<head>  contains the information about the HTML document. Whatever we write inside the head tag is not visible in our website.
<body>  whatever we write inside this body tag will be visible in our website. It contains everything we want to display on the web page.
<title>  Title for the HTML page
<h1>  Defines a large heading

<!DOCTYPE html>
<html>
	<head>
		<title> Home Page </title>
	</head>
	<body>
		<h1> Best HTML Course </h1>
	</body>
</html>
==================================================
How browsers determine the language of an HTML document?
<!DOCTYPE html>
<html lang=”en”>
en -> specifies the language code for the element’s content
lang -> The lang attribute specifies the language of the element’s content.
<html lang=”hi”>
hi-> hindi language
<html lang=”ko”>
ko-korean
<html lang=”fr”>
fr-french
===================================================
HTML Attributes
Attributes are used along with the HTML tags to define the characteristics of the element.
Attributes provide additional information about elements.
 
<!DOCTYPE html>
<html>
	<head>
		<title>Hello</title>
	</head>
	<body>
		<h1>World</h1>
	</body>
</html

=============================
HTML heading & text:-
Headings (<h1> to <h6>)
Paragraphs (<p>)
Line breaks (<br>)
Horizontal rule (<hr>)
===============================
HTML Headings:-
h1: Typically, larger and bold, around 24px to 36px or even larger.
h2: Slightly smaller, around 18px to 30px.
h3: Smaller than h2, around 16px to 24px.
h4: Generally, around 14px to 20px.
h5: Smaller, often around 12px to 18px
h6: The smallest, often around 10px to 16px.
=====================================
HTML Heading Elements:
The <h1> to <h6> tags create headings in HTML, where <h1> is the biggest and most important, and <h6> is the smallest and least important.
<!DOCTYPE html>
<html lang=”en”>
<head>
	<meta charset=”UTF-8”>
	<meta name=”viewport” content=”width=device-width, initial-scale=1.0”>
	<title>Document</title>
</head>
<body>
	<h1>Let’s Do it</h1>
</body>
</html>
Notes:- HTML HEADING ELEMENTS
The tag’s element name is case-insensitive.
A single H1 is typically used per page.
Follow the hierarchy from H1 to H6 consistently.
======================================================================
Interview Questions: HTML HEADING ELEMENTS
1.	How many levels of headings are available in HTML?
A.	6
2.	What is the default font size for HTML Headings?
A.	h1 ->24px – 36px
h2 ->18px -30px
h3 ->16px – 24px
h4 ->14px – 20px
h5 ->12px – 18px
h6 ->10px – 16px
3.	What happens if you skip heading levels, such as going from <h1> to <h3>
A.	Skipping heading levels can confuse both users and search engines. It’s best to maintain a proper hierarchical structure for better accessibility and SEO.
4.	How many <h1> tags can be used on a single page?
A.	Traditionally Approach: Use only one
<h1>tag for the main title or heading of the entire page</h1>
======================================================================
HTML PARAGRAPH TAG
<p> I am paragraph tag </p> -> HTML element
<p> -> Opening tag
I am paragraph tag -> content
</p> ->Closing Tag
The <p> tag defines a paragraph.
Browsers automatically add a single blank line before and after each <p> element.
Interview : HTML Paragraph Element
1.	How do you create a paragraph using the <p> tag?
A.	<p>This is how we create a paragraph</p>
2.	Can you nest other HTML elements inside a <p> tag?
A.	No, the <p> tag is a block-level element, and it cannot contain block-level elements like other paragraphs or headings. However, you can include inline elements like <strong>, <em>, and links.

we will see <br> and <hr> tag
<br> - line break
<hr> - horizontal line
Note:- No matter how much whitespace you use inside HTML element content (which can include one or more space characters, but also line breaks), the HTML parser reduces each sequence of whitespace to a single space when rendering the code.

HTML Comment Tag:-
<!- -Comment Here - ->
To comment out in HTML, insert information between <!- -and --> tags(browsers won’t show these notes).
	Commenting in HTML allows developers to leave notes about their code its functionality or to indicate necessary changes for the future reference.
HTML Text Formatting
1.	Bold and Italic:
<strong>, <em>
2.	Underline and Strikethrough:
<u>, <s>
3.	Subscript and Superscript:
<sub>, <sup>
4.	Preformatted Text:
<pre>, <kbd>, <abbr>
5.	Text Highlighting
<mark>, <small>, <del>
6.	Inline style
<p style=”color:red”>hello</p>

HTML formatting involves enhancing the visual presentation of text. It enables text manipulation for improved aesthetics, eliminating the need for CSS. Various formatting tags within HTML facilitate techniques such as bold, italics, and underline, enhancing the text’s visual prominence and emphasis.

Bold and Italic:-
<strong>: Represents strong importance. Text inside this tag is typically displayed as bold.
<em>: Represents emphasized text. Text inside this tag is usually displayed in italics.
Underline and strikethrough:-
<u>: Represents underlined text.
<s>: Represents strikethrough text (crossed out).
Subscript and Superscript:-
<sub>: Represents subscript text (lower and smaller)
<sup>: Represents superscript text(upper and smaller).
Preformatted text:-
<pre>: Represents preformatted text, preserving spaces and the breaks.
<kbd> tag: The <kbd> tag represents keyboard input, including that the enclosed content should be treated as something a user would type on a keyboard. It is often used to show example of keyboard commands or shortcuts.
<abbr> Tag: The <abbr> tag stands for “abbreviation” and is used to mark up abbreviations or acronyms in your content.
Text Highlighting:-
<mark> Tag:
The <mark> tag is used to highlight or mark a portion of text to draw attention to it. It typically results in a yellow background color behind the marked text, making it stand out visually.
<small Tag:
The <small> tag is used to indicate that the enclosed text should be displayed in a smaller font size. It’s often used for fine print, legal disclaimers, or less important information.
<del> tag:
The <del> tag is used to represent deleted or removed text in a document. Browsers typically render the text with a strike-through line to indicate that it has been deleted.
The <s> tag specifies text that is not longer correct, accurate or relevant. The <del> tag is used identify text that has been deleted from a document but retained to show the history of modifications made to the document.
Inline Styles:-
You can use inline CSS styles to apply formatting directly to specific text elements.

