===========================
Building the developer docs
===========================

Dependencies
============

You'll need to install python *Sphinx* package
package:

::

   sudo pip install sphinx

If you are using the virtualenv you'll need to install them in the
virtualenv.

Get Help
========

Just type make to get help:

::

   make

It will list available build targets.

Build Doc
=========

To build the man pages:

::

   make man

To build the developer documentation as HTML:

::

   make html

Type *make* for more formats.

Test Doc
========

If you modify doc files, you can type:

::

   make doctest

to check whether the format has problem.