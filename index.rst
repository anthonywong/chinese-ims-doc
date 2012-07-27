.. Chinese Input Methods master file, created by sphinx-quickstart on
   Fri Jul 27 22:38:40 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=====================
Chinese Input Methods
=====================

.. todo::

    Cross-reference sections, add anchors for each section for external
    referencing.

Written Chinese languages
=========================

There are mostly two written Chinese languages: Simplified and Traditional
Chinese.

.. note::
    If we forgot important other **written** Chinese languages, please let us
    know.

Mainland China writes in Simplified Chinese, while Hong Kong, Macau and Taiwan
write in Traditional Chinese.


Types of Chinese input methods
==============================

There are two big classes of Chinese input methods:

IM based on the sounds of words
-------------------------------

A user of those will type the romanization of the Chinese character, i.e how a
word in the Latin alphabet could be written to produce the sound of that
character.

For example, 我 ("I") is pronounced something like "wo". So a Pinyin user will
type those two characters, "w" then "o", and one of the suggestions will be 我.

.. todo::
    Get other examples of these.

Examples of these include Pinyin and XXX.

IM based on the strokes necessary to write a word
-------------------------------------------------

.. todo::
    Get someone to draw me a simple word, with corresponding keys.

These are based on the strokes necessary to write a character.

For example, with a pen and paper, to write XXX, one needs to first write
XXX, then XXX, and finally XXX. Much like when writing a "p", one would start
by "drawing" the vertical bar, then add the round part.

In an stroke-based input method, each type of stroke (vertical, horizontal,
curved, ...) is associated to a character of the latin alphabet on the
keyboard.

And then one has to type **in the right order** the series of characters
corresponding to the series of strokes necessary to write the full character.

Cangjie, Quick or hand-writing (either with pen and paper or with a touch
screen device) are all examples of stroke-based input methods.

Most used Chinese input methods
===============================

.. note::
    This document was written by people in Hong Kong. If we made any mistake
    for the other regions using Chinese input methods, please let us know.

The most used Chinese input methods are the following:

* Pinyin is a sound-based input method. It is used mostly in Mainland China,
  to input Simplified Chinese.
* Bopomofo is a XXX-based input method. It is used mostly in Taiwan, to input
  Traditional Chinese.
* Cangjie is a stroke-based input method. It is used mostly in Hong Kong, to
  input Traditional Chinese.
* Quick is a stroke-based input method. It is used mostly in Hong Kong, to
  input Traditional Chinese. Note that Quick is based on Cangjie.
* Hand-writing can be seen as a stroke-based input method. It is used
  everywhere people write on a piece of paper, or on a touch screen, to input
  any Chinese language.

The situation in Hong Kong
==========================

Cangjie and Quick
-----------------

.. todo::
    Write it up.

Multiple languages
------------------

.. todo::
    Write it up.

Different versions
------------------

.. todo::
    Write it up.

Schools and education
---------------------

Schools teach Cangjie version 3. This has a lot to do with inertia: Cangjie 3
is the default on Windows.

What people use
---------------

After learning at school, most people will move from Cangjie to Quick.

This is because the former has a much steeper learning curve than the latter,
which is much easier to use.

However, many people stick to Cangjie because, once they have made the effort
to learn it properly, it allows them to type much faster.

In any case, the overwhelming majority uses version 3 of their input method of
choice, with the rest using version 5.

Implementations on most popular OSes
------------------------------------

Windows
*******

Windows provides both Cangjie and Quick, both in version 3.

.. note::
    Windows is used by the virtually everybody in Hong Kong, both at home, at
    school and at work.

Since Windows 7, it offers to optionally enable the results of respective
version 5. But that is **in addition** to the results of version 3. This
option effectively enables what IBus calls "Cangjie Big".

Mac OS X
********

Mac OS X provides Cangjie and Quick, both in version 4.

Most Mac users of Cangjie in Hong Kong will install the Yahoo input method
framework instead of using the default system one, as it allows them to use
Cangjie 3 as they are used to.

Quick users tend to not bother. This is because, given the design of Quick,
very few things changed between versions 3 and 4.

GNOME
*****

.. note::
    This is pretty much a work in progress...

GNOME uses IBus as its Input Method Framework.

IBus provides implementations of Cangjie, Quick and Stroke 5 through
IBus Table.

For both Cangjie and Quick, versions 3 and 5 are available.

.. todo::
    Example of word.

IBus Table also provides what it calls Cangjie "Big", which is the combination
of both versions 3 and 5. For example, one can get the word 

For Quick, IBus Table also provides Quick "Classic", which is completely
obsolete these days.

Accessibility: Stroke 5
-----------------------

Stroke 5 is an input method which was created for the elderly and people with
reduced hand mobility.

It is stroke based, just like Cangjie and Quick.

However, to allow typing with few fingers and with relatively few movements,
only 5 keys are used:

.. todo::
    Give some more details...

In Hong Kong, some groups are showing tremendous results with Stroke 5, giving
access to electronic devices and the Internet to people who traditionally
couldn't input their own language on a keyboard before.

================================================================================

Languages:
Both designed to input Traditional Chinese, Simplified Chinese and Japanese.

IBus has a filter (called "Chinese Mode"):
- 0 => only candidates in Simplified Chinese
- 1 => only candidates in Traditional Chinese
- 2 => everything, but Simplified Chinese first
- 3 => everything, but Traditional Chinese first
- 4 => everything
