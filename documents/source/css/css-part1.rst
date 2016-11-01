.. include:: ../commondefs.rst

Part 1 - Where the magic happens
++++++++++++++++++++++++++++++++

Introduction to CSS
===================

- Open the file :filename:`discoveringCSS.html` in your browser and in your text editor.

- OK. Apparently, there is nothing new here.

- Now, search for the text :filename:`default.css` in the code, and replace it with :filename:`style1.css`.

- Save your edit and refresh your browser. Nice, isn't it? 

- Now, you can try to change :filename:`style1.css` in :filename:`style2.css`. 


What have we done to change the style of the page?
==================================================

We have used this special HTML element: **link**.

.. code-block:: html

   <link rel="stylesheet" href="style1.css">

The **link** element enables us to "include" other files in our web page.

Here, we have included a **Stylesheet** writen in **CSS** that gives instructions to change the look of the page.
                

What is CSS?
============

- CSS means Cascading StyleSheets.

- It is a special language to describe formating rules for web pages.

- For clarity, CSS rules are written in a separate file and are inculded in the HTML document *via* the **link** element. 


Let's see how CSS works!
========================

- Open the file :filename:`style1.css` and observe the code. 

- As you can see, the code is quite different from HTML code.

- However, you may recognise some HTML elements names.


What is a CSS rule?
===================

A CSS rule includes is composed of two main elements: a **selector**, and a set of properties.

- The selector (**em** in the example below) indicates on which elements the rule will be applied.

- The properties (between brackets)  enable to define the expected appearance of the selected element.

.. code-block:: html

   em{
      color: green;
      font-size: 20px;
   }

For example, this CSS rule means that all the **em** elements of your web page will be displayed in **green** and the size of the text will be **20px**. 
                
.. todo: faire un dessin à flèches. 


Want to see more examples?
==========================

If you want to have a look at what can be done with CSS, pay a visit to CSS Zen Garden website__

On this website, you can see the same web page with many different styles. It is impressive!

__ http://www.csszengarden.com/



