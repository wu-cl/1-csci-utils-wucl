========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        |
        | |codeclimate|
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/1-csci-utils-wucl/badge/?style=flat
    :target: https://readthedocs.org/projects/1-csci-utils-wucl
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/csci-e-29/1-csci-utils-wucl.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/csci-e-29/1-csci-utils-wucl

.. |codeclimate| image:: https://codeclimate.com/github/csci-e-29/1-csci-utils-wucl/badges/gpa.svg
   :target: https://codeclimate.com/github/csci-e-29/1-csci-utils-wucl
   :alt: CodeClimate Quality Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/csci-e-29/1-csci-utils-wucl/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/csci-e-29/1-csci-utils-wucl/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

Installation
============

::

    pip install csci-utils

You can also install the in-development version with::

    pip install https://github.com/csci-e-29/1-csci-utils-wucl/archive/master.zip


Documentation
=============


https://1-csci-utils-wucl.readthedocs.io/


Development
===========

To run the all tests run::

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
