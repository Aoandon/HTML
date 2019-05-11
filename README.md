# HTML-  HyperText Markup Language

# Introduction:

HTML-  HyperText Markup Language is the standard markup language for creating web pages and web applications. With Cascading Style Sheets (CSS) and JavaScript, it forms a triad of cornerstone technologies for the World Wide Web.


# History:

HTML was first created by Tim Berners-Lee, Robert Cailliau, and others starting in 1989. It stands for Hyper Text Markup Language.
Hypertext means that the document contains links that allow the reader to jump to other places in the document or to another document altogether. The latest version is known as HTML5.
A Markup Language is a way that computers speak to each other to control how text is processed and presented. To do this HTML uses two things: tags and attributes.

# HTML5

## HTML5 new elements 

Tag | Description 
------------ | -------------
&lt;article&gt; | Defines an article in a document
&lt;aside&gt; | Defines content aside from the page content
&lt;bdi&gt; | Isolates a part of text that might be formatted in a different direction from other text outside it
&lt;details&gt; |  Defines additional details that the user can view or hide
&lt;dialog&gt; | Defines a dialog box or window
&lt;figcaption&gt; |  Defines a caption for a <figure> element
&lt;figure&gt; |  Defines self-contained content
&lt;footer&gt; |  Defines a footer for a document or section
&lt;header&gt; | Defines a header for a document or section
&lt;main&gt; | Defines the main content of a document
&lt;mark&gt; | Defines marked/highlighted text
&lt;meter&gt; |  Defines a scalar measurement within a known range (a gauge)
&lt;progress&gt; | Defines navigation links
&lt;rp&gt; |  Defines what to show in browsers that do not support ruby annotations
&lt;rt&gt; | Defines an explanation/pronunciation of characters (for East Asian typography)
&lt;ruby&gt; |  Defines a ruby annotation (for East Asian typography)
&lt;section&gt; | Defines a section in a document
&lt;summary&gt; |Defines a visible heading for a <details> element
&lt;time&gt; |Defines a date/time
&lt;wbr&gt; |Defines a possible line-break
  
## This is a basic html page with some of tags you need for start build application.

<pre><code>
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;Title&lt;/title&gt;
&lt;<a href="/tags/meta/">meta</a> charset="UTF-8"&gt;
&lt;<a href="/attributes/meta-name/">meta name</a>="description" content="This field contains information about your page. It is usually around two sentences long."&gt
&lt;meta name="author" content="Conor Sheils"&gt;
&lt;link rel="stylesheet" href="style.css"&gt;
&lt;/header&gt;
&lt;body&gt;

&lt;header&gt;
  &lt;div class="container"&gt;
    &lt;nav id="nav-bar"&gt; //Navigation
      &lt;ul&gt;
        &lt;li&gt;&lt;a href=""&gt;Home&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;About&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=""&gt;Contact&lt;/a&gt;&lt;/li&gt;
      &lt;/ul&gt;
    &lt;/nav&gt;
  &lt;/div&gt;
 &lt;header&gt;

  &lt;section id="intro"&gt; //New HTML5 Syntax ID= unique you can use one time the same id
   &lt;div class="container"&gt; //Create division for you control in CSS4 class=can you use the same class many times you want
       &lt;h1&gt; Title &lt;h1&gt; // Title h1
        &lt;p&gt; Paragraph &lt;p&gt; //paragraph 
   &lt;/div&gt;
  &lt;/section&gt;

  &lt;section id="middle"&gt; 
   &lt;div class="container"&gt; 
      &lt;div class="row"&gt; 
       &lt;h1&gt; Row1 &lt;h1&gt; 
       &lt;p&gt; Paragraph &lt;p&gt;
      &lt;/div&gt;
        &lt;div class="row"&gt; 
       &lt;h1&gt; Row2 &lt;h1&gt; 
       &lt;p&gt; Paragraph &lt;p&gt;
      &lt;/div&gt;
        &lt;div class="row"&gt; 
       &lt;h1&gt; Row3 &lt;h1&gt; 
       &lt;p&gt; Paragraph &lt;p&gt;
      &lt;/div&gt;
   &lt;/div&gt;
  &lt;/section&gt;
  
  
&lt;/body&gt;
&lt;/html&gt;
</code></pre>

# Syntax: 
