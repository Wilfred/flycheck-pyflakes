flycheck-pyflakes
=================

[![MELPA](http://melpa.org/packages/flycheck-pyflakes-badge.svg)](http://melpa.org/#/flycheck-pyflakes)

Flycheck already has great support for Python if you want to use
pylint or flake8.

Howerver, pylint is sometimes too smart and is prone to false
positives. flake8 warns about both dodgy code (from pyflakes) and PEP
8 violations. When you're fixing bugs in other people's code, you
don't care about style issues. flake8 doesn't provide any way of
switching off all the styling warnings.

Instead, this package lets you use pyflakes alone.
