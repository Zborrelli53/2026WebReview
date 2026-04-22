# 2026WebReview
    HTML review

    what does HTML stand for'?
    Hypertext Markup Language

    What is the difference between <head> and <body>
        <head> --> Metadata - read by the browser

        <body> --> This content is Displayed in the browser

Name THREE semantic HTML elements.
<header></header>
<footer></footer>
<main></main>
<nav></nav>
<article></article>
<aside></aside>
<section></section>

What attribute does an <a> need to create a link?
    href --> <a href="https://www.google.com">

What is a self closing HTML tag? Give an example
Are tags that do not have closing tags, also known as Void Elements
<br>
<img>
<link>
<meta>

What does <!DOCTYPE html> do?
This tells the browser that the file is an HTML file

Every HTML file has the same SKELETON (Boilerplate, template) structure (in an HTML file on mac, CMND + SHIFT + ! automatically makes the skeleton):

<!DOCTYPE html>
<html>
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", initial-scale="1.0">
         - Makes the page Responsive
</head>
<body>
    <header>
    <nav>Contains any Navigation Bar elements</nav>
    </header>
    <h1>Largest heading/most important heading. Only once per page</h1>
    <!-- All VISIBLE elements go inside the body -->
</body>

</html>

PART 2: Core HTML Elements
Headings 1 - 6
<h1> --> There should only be 1 <h1> per page
<h2> --> section titles, subtitles
<h3> --> subs-ections
<h4> --> 
<h5> --> Fine Print (Copyright statements, etc)
<h6> --> FIne Print (Copyright statements, etc)

Text Elements
<p> --> paragraph tag
<strong> --> Bold/Important text
<em> --> italic / emphasized text
<br> --> line break (void element)
<u> --> underline
<hr> --> Horizontal row --> visual line divider (void element)
<span> --> inline element, does not create a line break
<mark> --> Highlights text

HTML Lists

Unordered List --> Bulleted list
- Used for: Items with no ranking order
<ul>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ul>

Ordered List --> Numbered/Alphabetized
- used for steps, rankings, sequences, etc.
<ol>
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ol>

