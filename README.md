# my-first-website
Where the magic happens

As I've been wanting to learn how to create a website with three.js for a year now but I know absolutely nothing about hosting and all that shit about servers and all the things related to creating a simple website (html, css, javascript, etc.) I finally decided to try

You can follow, if you want, the progress of my first website. I will also put a textual description (the theory) of how to do it so you can do it from scratch by yourself

I will try to understand what is html, css javascript and try to code something minimalist with a library that fascinates me: three.js

Let's try something easy first:

<img width="500" alt="image" src="https://user-images.githubusercontent.com/84352348/227739002-bdf966bc-6809-4066-9e69-d09c6e0ea12d.png">

OK. I admit. Not so pretty for now, I know. But I have some great ideas stuck in my head


<h1> First steps into website coding </h1>

<p> After a minute of research, all the base of a website is made thanks to an HTML file. Then a CSS file to make it more beautiful. And finally with javascript files to make your site more interactive  </p>

<p> HTML and CSS are very related, but they don't work in the same way. HTML is the skeleton of a website and CSS is the skin, the hair and everything else that is pretty (even if a skeleton is also very beautiful). </p>

<h2> HTML </h2>

<h3> What I've learned so far </h3>

- There are several "versions" of HTML. That's why at the beginning of each .html file you have to define which "version" you are using so that the computer interprets it in the right way: !DOCTYPE html 

- Then any file must start and end with the html /html tag so we know which part of the code is html.

- Information about the web page, like the title, belongs within the "head" of the page.

- Anchor tags ("a") are used to link to internal pages, external pages or content on the same page.
- Comments are written in HTML using the following syntax: "!-- comment --"
- You just need to know everything you can do with HTML to create a site easily. Here are some elements that you can create in a few clicks (and then rearrange in a nice design)
  - The titles: "h1", "h2", "h3", "h4"...
  - Images: "img"
  - Videos: "video"
  - Divide your code in little part swith "div"
  - Paragraphs: "p"
  - Tables: "table", "thead" & "th" (table head), "tbody", "tr" (table rows), "td" (table data), "tfoot"
  - Links: "a"
  - Ordered or disordered lists: "ol", "ul", "li"
  - Forms to collect some data: "form", "input" (to take the input of the user), "label" (to indicate which data they need to enter)
    - For sensitive content, it exists a type="password" attribute for "input"
    - You can create a lot of different inputs: checkbox, text, numbers, ranges, radio (only one input allowed), a dropdown list, a datalist (so the user can write smthg and the list will propose the most similar answer), a textarea element and obviously a submit button
    - You can add a client-side validation to the form (with required, max, min, maxlength & minlength)
  - Audios
- A good website has a header, a footer, a navigation section, sections (elements in a document), articles (+ asides, figures, figcaption) and a main content.

<h2> CSS <h2>

<h3> What I've learned so far </h3>

You can style any website using HTML. 
- We can specify global styles (e.g. make all h1 titles have the same characteristic), or specify each block of our website using classes (or IDs).
  -  Difference between classes and IDs: (to complete)
- You can also style attributes (images, links, videos, etc.): a[href*="name of variable"] { }
- If you want to style elements just after a certain action, you can use pseudo-classes. For example, we can say that we want our paragraphs to turn purple when we hover over them. We just need to write p:hover and the desired color.
