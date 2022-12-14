.. image:: https://jazzband.co/static/img/badge.svg
   :target: https://jazzband.co/
   :alt: Jazzband

.. image:: https://readthedocs.org/projects/contextlib2/badge/?version=latest
   :target: https://contextlib2.readthedocs.org/
   :alt: Latest Docs

.. image:: https://img.shields.io/travis/jazzband/contextlib2/master.svg
   :target: http://travis-ci.org/jazzband/contextlib2

.. image:: https://coveralls.io/repos/github/jazzband/contextlib2/badge.svg?branch=master
   :target: https://coveralls.io/github/jazzband/contextlib2?branch=master

.. image:: https://landscape.io/github/jazzband/contextlib2/master/landscape.svg
   :target: https://landscape.io/github/jazzband/contextlib2/

contextlib2 is a backport of the `standard library's contextlib
module <https://docs.python.org/3.5/library/contextlib.html>`_ to
earlier Python versions.

It also serves as a real world proving ground for possible future
enhancements to the standard library version.

Development
-----------

contextlib2 has no runtime dependencies, but requires ``unittest2`` for testing
on Python 2.x, as well as ``setuptools`` and ``wheel`` to generate universal
wheel archives.

Local testing is just a matter of running ``python test_contextlib2.py``.

You can test against multiple versions of Python with
`tox <https://tox.testrun.org/>`_::

    pip install tox
    tox

Versions currently tested in both tox and Travis CI are:

* CPython 2.7
* CPython 3.4
* CPython 3.5
* CPython 3.6
* CPython 3.7
* PyPy
* PyPy3
