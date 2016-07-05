General
=======

Editorconfig
============

Deviation from Pep 8
====================
* line length


* Sort imports alphabetically. Use ``isort``.
* Declare encoding in first line: ``-*- encoding: utf-8 -*-``

Code-Style
===========
* Favour multiple small specialized (local) functions/methods over big all encompasing ones.
* Use well established and maintained high quality 3rd party libraries over own implementations.
* Use expressive variable names. If you have to trade off verbosity and expressiveness, go for the
  later.
* Assigning variables even if they are used only once can be preferable if expressions become clearer
  and less dense.
* Prefer clear structure and readability over clever code.


Documentation
=============
* Docstrings for all public and private classes, methods functions. Simple local
  functions may go without. Use them elaborate their signature and use.
* Use ``google-style`` for readable docstrings. Sphinx ``napoleon`` extension will
  make turn this into valid ``rst``.
* Use block comments to explain implementation 


