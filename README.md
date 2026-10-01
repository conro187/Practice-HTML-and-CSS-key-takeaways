# Practice-HTML-and-CSS-key-takeaways
Practice: HTML and CSS key takeaways


Let's practice what we've learned about HTML! Write a listicle in about 500 words, formatted in HTML, that describes 3 "key takeaways" about HTML.
For this assignment, you should start a new GitHub project and write your listicle in HTML format. 

#What I was able to do on my own
===========================================================================================================================

Apply some basic CSS styles to your document, such as background color or text color for certain elements to help information stand out. Your CSS may be applied with a <link> relationship, as a <style> block, or using style= attributes.

<h1 style="color:blue; background-color:powderblue;">Blue Heading</h1>
<p style="color:red; background-color:tomato;">Red Paragraph</p>

color sets the text color, background color sets the background color. 

<!DOCTYPE html>
<html>
<head>
<style>
  body {  background-color: powderblue;}
  h1 {  color: blue; }  p {   color: red; }
</style></head><body><h1>This is a heading</h1><p>This is a paragraph.</p></body> </html>.n

body { background-color: powderblue; }
h1 { color: blue; }
p { color: red; }

This is all I could find for how to add colors. I do not think I did it successfully however I did try numerous times. 

##What I did after using google, class notes, AI and other resources
===============================================================================================================================

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>3 Key Takeaways About HTML</title> <style> body { font-family: Arial, sans-serif; line-height: 1.6; background-color: #f4f7fb; color: #222; max-width: 900px; margin: 0 auto; padding: 30px; } header { background-color: #264653; color: white; padding: 25px; border-radius: 10px; text-align: center; } h2 { color: #e76f51; } .takeaway { background-color: white; padding: 20px; margin: 20px 0; border-left: 6px solid #2a9d8f; border-radius: 6px; box-shadow: 0 2px 6px rgba(0, 0, 0, 0.08); } .important { color: #d62828; font-weight: bold; } code { background-color: #eef1f5; padding: 2px 5px; border-radius: 3px; } footer { text-align: center; margin-top: 30px; color: #666; } </style> </head> <body> <header> <h1>3 Key Takeaways About HTML</h1> <p>A short guide to understanding the foundation of web pages</p> </header> <main> <article class="takeaway"> <h2>1. HTML Gives a Web Page Its Structure</h2>
  <p>
    HTML, or HyperText Markup Language, is the language used to organize
    the content of a web page. Rather than controlling how a page looks,
    HTML describes what different pieces of content are. For example,
    headings, paragraphs, links, images, and lists can all be represented
    with HTML elements.
  </p>

  <p>
    Elements are usually written using opening and closing tags. A
    paragraph might look like <code>&lt;p&gt;Hello!&lt;/p&gt;</code>.
    This structure allows browsers to understand how information should
    be organized and displayed. One important takeaway is that
    <span class="important">HTML provides the foundation</span> on which
    the rest of a web page is built.
  </p>
</article>

<article class="takeaway">
  <h2>2. Semantic HTML Makes Content More Meaningful</h2>

  <p>
    HTML is not just about making content appear on a screen. Modern HTML
    includes semantic elements that communicate the purpose of different
    sections. Examples include <code>&lt;header&gt;</code>,
    <code>&lt;main&gt;</code>, <code>&lt;article&gt;</code>,
    <code>&lt;nav&gt;</code>, and <code>&lt;footer&gt;</code>.
  </p>

  <p>
    Using semantic HTML can make a document easier for people and
    technologies to understand. Screen readers and other assistive
    technologies can use the structure to help users navigate a page.
    Semantic markup can also make source code easier for developers and
    technical writers to read and maintain.
  </p>
</article>

<article class="takeaway">
  <h2>3. HTML and CSS Work Together</h2>

  <p>
    HTML and CSS have different jobs, but they work particularly well
    together. HTML describes the content and structure of a page, while
    CSS controls its visual presentation. CSS can change colors, fonts,
    spacing, borders, backgrounds, and layouts.
  </p>

  <p>
    For example, an HTML heading such as
    <code>&lt;h1&gt;My Website&lt;/h1&gt;</code> provides the content and
    structure. CSS can then make that heading larger, change its color,
    or position it differently. Separating structure from presentation
    makes it possible to create attractive pages without changing the
    underlying content.
  </p>

  <p>
    Learning how HTML and CSS complement each other is an important step
    toward creating websites that are both <span class="important">
    organized and visually engaging</span>.
  </p>
</article>

</main> <footer> <p>Created as an HTML and CSS practice project.</p> </footer> </body> </html>
