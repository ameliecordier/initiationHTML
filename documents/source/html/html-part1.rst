.. include:: ../commondefs.rst

==========================
Part 1 - Elements and tags
==========================


Step 1 - Two sides of an HTML page: code and display
====================================================

- Open :filename:`page0.html` in a web browser. Don't close it. 
- Open :filename:`page0.html` in a text editor and observe the code. Don't close this file neither.
- Learn to switch between the text editor and the browser, for example, by using ``Alt+Tab`` on the keyboard.


Step 2 - Your first edit
========================

- Edit the code of the :filename:`page0.html` in the text editor. For example, add your **firstname** where it should be. 
- Save your changes in the text editor.
- Reload the page in the browser and make sure your changes are visible.

.. warning:: Learn the shortcuts: :shortcut:`F5` to reload the page in the browser, :shortcut:`Ctrl+S` to save your file in the editor. 


Remember...
===========

- Do not forget to save your edits in the text editor before refreshing a page.
- You do not need to close the editor nor the web browser.
- The ``Alt+Tab`` shortcut is convenient to switch between the two applications.


Step 3 - HTML tags
==================

HTML is based on :dfn:`elements`. An element indicates that a part of the document has a specific role.

For example, if you want to stress your name in the sentence, you can use the :html:`em` element.

The :html:`em` element is identified by a start tag and a end tag. 

Here is an example. Try it!

.. code-block:: html

   My name is <em>Amélie</em>


And this is the result:

.. raw:: html

   <section class="rendered">
     My name is <em>Amélie</em>
   </section>


Understanding HTML tags
=======================

Most of the time, HTML elements have a *start tag* and a *end tag*.

Tags names are written inside angle brackets (greater than & less than symbols: “<” & “>”)

In the end tag, the tag name is preceded with a forward slash (/) sign.

For the element **em**, the start tag and end tag are:

.. code-block:: html

   <em> and </em>

.. todo mettre une figure de tag avec des flèches sur chacun des éléments


Step 4 - Let's try another tag
==============================

This is your **first** web page, it is very important!

Try to use the :html:`<strong>` tag around the word **first** in the web page.

Admire the result in your browser.


Step 5 - More HTML tags
=======================

- Open :filename:`page1.html` on your text editor and on your web browser (a good idea is to use a new tab in both cases).
- Hum... the presentation is not what we expect. Let's change that!
    - The tag :html:`<h1>` is for headings. Use it to define the title of the page.
    - The tag :html:`<p>` is for paragraph. Try it!
- Check the result on your web browser.


Step 6 - Image (1/3)
====================

It's time to add an image in your page.

The element for including an image is **em** and the corresponding tag is :html:`<img>`.

Here is an example:

.. code-block:: html

   <img src="TBL.jpg" alt="Inventor of the Web: Tim Berners Lee">

And this is the result:

.. raw:: html

   <section class="rendered">
         <img width="45%" style="float:right;" src="../_static/TBL.jpg" alt="Inventor of the Web: Tim Berners Lee">
   </section>


Step 6 - Image (2/3)
====================
         
.. code-block:: html

   <img src="mypicture.png" alt="This is my picture">

This tag has something new: ``alt`` and ``src`` are *attributes*.

Attributes specify behaviors of the tag.

Here, the ``src`` attribute indicates where to find the image, and the ``alt`` attribute defines an alternative text that will be displayed if the image cannot be loaded. 

.. warning:: An :html:`img` tag does not need a closing tag.
   It is quite rare.
             

Step 6 - Image (3/3)
====================

Using the :html:`img` tag you have just learned, include in :filename:`page1.html` a photo of *Sir Tim Berners Lee*. You will find and image in the directory named :filename:`images`.

Be careful, as the photo is in the :filename:`images` directory, and because it is named "Sir_Tim_Berners_Lee.jpg", the ``alt`` attribute should be: ``alt="images/Sir_Tim_Berners_Lee.jpg``.


Step 7 - Links
==============
   
HyperText is all about links... so let's make **links**.

There are two types of links: internal links (between your pages) and external links (to the web).
In both cases we use the same tag.

Let's see an example:

.. code-block:: html

  <a href="http://www.w3c.org">Click here to go to the W3C web page</a>

Like the :html:`img` tag, the :html:`a` tag has an attribute: ``href``.

Like most of the other tags, the :html:`a` element has a start and a end tag.

Step 7 - Links
==============

Using the tag you've just learned (see below), add a link around the address at the bottom of the page.

.. code-block:: html

  <a href="http://www.w3c.org">Click here to go to the W3C web page</a>


Try it in your browser! 


Step 7 - Internal links
=======================

Making internal links is like making external links.

The only difference is that the ``href`` attribute of the :html:`a` tag contains the name of the page you want to link instead of a web address.

For example, if you have two pages in the same directory, say :filename:`page0.html` and :filename:`page1.html`, then, on :filename:`page0.html`, you can add the following code:


.. code-block:: html

   <a href="page1.html">This is a link to page 1</a>

It's your time to try!

**Add links** on your pages and make sure you are able to navigate from one page to the other, and back.


Summary
=======

HTML is the language we use to build web pages.

A web browser reads HTML code and interprets it to display the corresponding web page.

HTML defines many elements and is written with tags (start tag and end tag) such as :html:`<p>` and :html:`</p>`.

Some elements may have attributes such as in the followig example:

.. code-block:: html

   <a href="page3.html">This is a link to page 3</a>














