:css: style.css

.. title:: My Presentation

----

:data-x: r2200
:data-y: 0
:class: cover-class

.. image:: images/sample-title.jpg

Main Title
==========

Subtitle
--------

Speaker name

.. note::

  To remove the title image, remove the image on the cover slide

----

Text and Stuff
==============

Just write some text here.
It will be formatted automagically as block.

Or on a new line

* There can be 
* also lists.

1. And counted
2. lists

* And levels
    * too

----

Images
======

Images are normally shown inline.

And can be also sized with `:width:` or `:height:`

.. image:: images/sample-title.jpg
   :width: 400px

----

:class: right-class

Images
======

With a special class `right-class` for a slide all images will try to go to the right.

.. image:: images/sample-title.jpg
  :width: 600px

----

:class: full-slide-class

Images
======

.. image:: images/sample-title.jpg

Also a image fullscreen slide is possible with `full-slide-class`. The image is then scaled to the maximum width.

----

Code
====

Code samples and inline code are also possible.

`final String test = "test";`

.. code-block:: java

  String test = "test";
  final String test = "test";

----

:class: right-class

Code
====

With the `right-class` class code blocks will also go to the right.

.. code-block:: java

  String test = "test";
  final String test = "test";

----

Presenter Notes
===============

By pressing `P` the presenter notes with the given notes will show up.

.. note::

  Welcome to the presenter view!

----


:data-x: r0
:data-y: r1200

More
====

The full documentation for hovercraft is available here: https://hovercraft.readthedocs.io/en/latest/presentations.html