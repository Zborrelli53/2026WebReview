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

Every HTML file has the same SKELETON (Boilerplate, template) structure (in an HTML file, shift + ! + tab creates the skeleton automatically):

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

Links

How do I create a link to sllboces.org?
<a href="https://sllboces.org" target="_blank">SLL Boces</a>

How do I create a link to about.html - a relative path (page in the same directory)
<a href="about.html">About</a>

Link to a file ikn the content folder?
<a href="content/page.html">Page</a>

A link to another section of the page?
<a href="#about">Jump to the About section</a>

A link to send an email?
<a href="mailto:cte-zander.borrelli@sllboces.org">Email Me</a>

Images
What are the two required attributes for <img> tags?
alt - accessibility text
src - file path to the image

<img src="images/hero.jpg" alt="Adirondack Mountains in fall">
<img src="images/logo.png" alt="SLL BOCES Logo">

What is hot-linking an image?
- Linking to an image somewhere on the internet
- Placeholder images for design purposes
- Replace hotlinks before publishing the site
- Why? If the hotlinked image gets moves, it will break your design

<img src="https://google.com/2/abc/file/images/myGoogleImage.png" alt="my hotlinked image">


Part 3
What is a semantic HTML element?
semantic elements describe the meaning of the content inside of the element, not just the way it looks

Reason why we use semantic elements?
Organization (Teamwork) - allows other developers to more easily read and understand your code

Effects the Document Object model - How the browser reads or understands the content

Accessibility - allows screen readers to understand the structure and meaning behind content

SEO - Search Engine Optimization - how search engines rank well-structured pages - moves them higher in the search results

Semantic tags replaced the use of <div> tags:
    <div class="header"> vs <header>

Layout Semantic Elements: header, nav, main, section, aside, and footer

Content Semantics Elements:
<figure></figure> - Image with a caption
<figcaption> - caption for a figure Image
<time> - a date or time value
<address> - contact address info
<mark> - highlighted text
<details> / <summary> - expand and collapse more details
<div> - non-semantic container
