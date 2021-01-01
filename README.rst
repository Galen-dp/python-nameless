========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-nameless/badge/?style=flat
    :target: https://readthedocs.org/projects/python-nameless
    :alt: Documentation Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/Galen-dp/python-nameless/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Galen-dp/python-nameless/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 3-Clause License

Installation
============

::

    pip install nameless

You can also install the in-development version with::

    pip install https://github.com/Galen-dp/python-nameless/archive/master.zip


Documentation
=============


https://python-nameless.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
