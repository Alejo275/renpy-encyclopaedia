Encyclopaedia Framework for Ren'Py
==================================

.. image:: https://api.travis-ci.org/jsfehler/renpy-encyclopaedia.svg?branch=master
    :target: https://travis-ci.org/jsfehler/renpy-encyclopaedia
    :alt: See Build Status on Travis CI

A plugin for the `Ren'py Visual Novel engine <https://www.renpy.org/>`_

Simplifies creating an encyclopaedia, bestiary, glossary, or similar system.

Compatible Ren'Py Version: 6.99.12.3 and higher


Documentation
-------------
Documentation is available at http://renpy-encyclopaedia.readthedocs.io/en/latest/index.html.

Development
-----------
Requirements: `tox`

`Tox <https://tox.readthedocs.io/en/latest/>`_ is used for managing the test environments.

Running the unit tests
~~~~~~~~~~~~~~~~~~~~~~

The unit tests can be run in any of the follow envs: py27, py33, py34, py35, py36, pypy


.. code-block:: console

    tox -e {env}

Running the code linter
~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: console

    tox -e flake8


Building the distribution file
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: console

    tox -e build
