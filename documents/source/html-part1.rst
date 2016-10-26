:tocdepth: 2

=================================
HTML - Part 1 - Elements and tags
=================================


Step 1 - Two sides of an HTML page: code and display
====================================================

- Open :filename:`page0.html` in a web browser. Don't close it. 
- Open :filename:`page0.html` in a text editor and observe the code. Don't close this file neither.
- Learn to switch between the text editor and the browser, for example, by using ``Alt+Tab`` on the keyboard.


Step 2 - Your first edit
========================

- Edit the code of the webpage in the text editor. For example, add your name where it should be. 
- Save your changes in the text editor.
- Reload the page in the browser and make sure your changes are visible.


Remember...
===========

- Do not forget to save your edits in the text editor before refreshing a page.
- You do not need to close the editor nor the web browser.
- The ``Alt+Tab`` shortcut is convenient to switch between the two applications.


Step 3 - HTML tags
==================

HTML is based on elements. An element indicates that a part of the document as a specific role.

For example, if you want to stress your name in the sentence, you can use the :html:`em` element.

The :html:`em` element is identified by a start tag and a end tag. 

Here is an example. Try it!

.. html-raw::

   My name is <em>Amélie</em>

.. todo : mettre le résultat 


Understanding HTML tags
=======================

Most of the time, HTML elements have a *start tag* and a *end tag*.

Tags names are written inside angle brackets the greater than & less than symbols “<” & “>”)

In the end tag, the tag name is preceded with a forward slash (/) sign.

.. todo mettre une figure
.. todo vérifier que la syntaxe passe bien 

Step 4 - Let's try another tag
==============================

This is your **first** web page, it is very important. Try to use the :html:`<strong>` tag around the word **first** in the web page.


Step 5 - More HTML tags
=======================

- Open :filename:`page1.html` on your text editor and on your web browser (a good idea is to use a new tab in both cases).
- Hum... the presentation is not what we expect. Let's change that!
    - The tag :html:`<h1>` is for headings. Use it to define the title of the page.
    - The tag :html:`<p>` is for paragraph. Try it!
- Check the result on your web browser.


Step 6 - Image (1/2)
====================

It's time to add an image in your page.

The tag for including an image is :html:`<img>`.

Here is an example:

<img src="mypicture.png" alt="This is my picture">

This tag has something new: ``alt`` and ``src`` are *attributes*. They specify some behaviors of the tag.

Here, the ``src`` attribute indicates where to find the image in the hard drive, and the ``alt`` attribute defines an alternative text that will be displayed if the image cannot be loaded. 

.. warning:: An :html:`img` tag does not need a closing tag. 

Step 6 - Image (2/2)
====================

Using the :html:`img` tag you just learned, include in :filename:`page1.html` a photo of *Sir Tim Berners Lee*. You will find and image in the directory :filename:`images`.

Be careful, as the photo is in the :filename:`images` directory, the ``alt`` attribute should look like ``alt="images/Sir_Tim_Berners_Lee.jpg``.


Step 7 - Links
==============
   
HyperText is all about links... so let's make links.

There are two types of links: internal links (between your pages) and external links (to the web).
In both cases we use the same tag.

.. TODO gérer la mise en forme 
<a href="http://www.w3c.org">Click here to go to the W3C web page</a>

Like the :html:`img` tag, the :html:`a` tag has an attribute: ``href``.

Like most of the other tags, the :html:`a` element has a start and a end tag.

Step 7 - Links
==============

Using the tag you've just learned, add a link around the address at the bottom of the page.


Step 7 - Internal links
=======================

Making internal links is like making external links.

The only difference is that the ``href`` attribute of the :html:`a` tag contains the name of the page you want to link instead of a web address.

For example, if you have two pages in the same directory, say :filename:`page0.html` and :filename:`page1.html`, then, on :filename:`page0.html`, you can add the following code:

<a href="page1.html">This is a link to page 1</a>

It's your time to try...

Add links on your pages and make sure you are able to navigate from one page to the other, and back.


Summary
=======

HTML is the language we use to build web pages.

A web browser reads HTML code and interprets it to display the corresponding web page.

HTML defines many elements and is written with tags (start tag and end tag) such as :html:`<p>` and :html:`</p>`.

Some elements may have attributes such as :html:`<a href="page3.html">This is a link to page 3</a>`














