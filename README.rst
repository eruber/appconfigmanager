=========================
AppConfigManager Overview
=========================

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/appconfigmanager/badge/?style=flat
    :target: https://readthedocs.org/projects/appconfigmanager
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/eruber/appconfigmanager.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/eruber/appconfigmanager

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/eruber/appconfigmanager?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/eruber/appconfigmanager

.. |requires| image:: https://requires.io/github/eruber/appconfigmanager/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/eruber/appconfigmanager/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/eruber/appconfigmanager/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/eruber/appconfigmanager

.. |version| image:: https://img.shields.io/pypi/v/appconfigmanager.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/appconfigmanager

.. |commits-since| image:: https://img.shields.io/github/commits-since/eruber/appconfigmanager/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/eruber/appconfigmanager/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/appconfigmanager.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/appconfigmanager

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/appconfigmanager.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/appconfigmanager

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/appconfigmanager.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/appconfigmanager


.. end-badges

Application config manager that syncs registered CLI options to the CFG file & supports use of PyQtConfig for Qt
applications.

* Free software: MIT license

Installation
============

::

    pip install appconfigmanager

Documentation
=============

https://appconfigmanager.readthedocs.io/

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
