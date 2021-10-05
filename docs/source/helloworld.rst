.. _interhyperlinkSpot:

Hello Titles! Notice the equally long equals signs
=======================================================

Make changes by cd docs, make html. Make sure you have the venv selected

This is how you make a hyperlink, by writing :ref:`genindex`
 you can also do extermal links `like this <http://cnn.com>`_ or even 

 like this: 'a link'_.

 .. _a link: https://tesla.com/

You can reference different parts in the same doc with 
Learn how to :ref:`link to a different section<interhyperlinkSpot>`.

A subheading
---------------

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2

Since Pythagoras, we know that :math:`a^2 + b^2 = c^2`.

No space between last word and bracket!

also\ *this*\ is italics
and\ **this**\ is bold and 
'''
this is code. None of this can start with whitespace and needs to be
separated from non text with backslash and space
'''
\ 
Code can also be::

    made like this, with blank lines

Nice!

* this is a bullet list

    * and a nested list, needs blank lines from parent

* with two items

1. And a numbered list


#. And a numbered list but without needing the numbers


| I can preserve line breaks with
| OR signs at the front


.. image:: images/firefox.png
    :width: 200px
    :height: 100px
    :scale: 50 %
    :alt: alternate text
    :align: center


testing

Inline image with |somename|.

.. |somename| image:: images/firefox.png
    :scale: 5 %

.. admonition:: Your title here

    Text goes here