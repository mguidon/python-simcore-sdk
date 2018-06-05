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
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-simcore-sdk/badge/?style=flat
    :target: https://readthedocs.org/projects/python-simcore-sdk
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/mguidon/python-simcore-sdk.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/mguidon/python-simcore-sdk

.. |codecov| image:: https://codecov.io/github/mguidon/python-simcore-sdk/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/mguidon/python-simcore-sdk

.. |version| image:: https://img.shields.io/pypi/v/simcore-sdk.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/simcore-sdk

.. |commits-since| image:: https://img.shields.io/github/commits-since/mguidon/python-simcore-sdk/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/mguidon/python-simcore-sdk/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/simcore-sdk.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/simcore-sdk

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/simcore-sdk.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/simcore-sdk

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/simcore-sdk.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/simcore-sdk


.. end-badges

Simcore Python SDK

* Free software: MIT license

Installation
============

::

    pip install simcore-sdk

Documentation
=============

https://python-simcore-sdk.readthedocs.io/

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
