========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/test_import/badge/?style=flat
    :target: https://test_import.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/enricofacca/test_import/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/enricofacca/test_import/actions

.. |requires| image:: https://requires.io/github/enricofacca/test_import/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/enricofacca/test_import/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/enricofacca/test_import/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/enricofacca/test_import

.. |version| image:: https://img.shields.io/pypi/v/test-import.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/test-import

.. |wheel| image:: https://img.shields.io/pypi/wheel/test-import.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/test-import

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/test-import.svg
    :alt: Supported versions
    :target: https://pypi.org/project/test-import

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/test-import.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/test-import

.. |commits-since| image:: https://img.shields.io/github/commits-since/enricofacca/test_import/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/enricofacca/test_import/compare/v0.0.0...main



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install test-import

You can also install the in-development version with::

    pip install https://github.com/enricofacca/test_import/archive/main.zip


Documentation
=============


https://test_import.readthedocs.io/


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
