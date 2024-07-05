=================
pre-commit-python
=================

A pre-commit for Python projects

.. contents:: Table of Contents

Introduction
============

This is a simple pre-commit for Python projects, to be used as a git hook.
It uses standard hooks like:

- black
- isort
- bandit

The aim is to maintain consistent code quality and enforce some security checks or protect against inadvertent committing of secrets.

Usage
=====

You should already have the pre-commit package installed. See `here <https://pre-commit.com/>`_ for details

Install the git hook scripts:

.. code-block:: bash

   pre-commit install

Run against a single file:

.. code-block:: bash

   pre-commit run --files <your file>

Run against all the staged files:

.. code-block:: bash

   pre-commit run --all-files

Auto-update to the latest repos' versions:

.. code-block:: bash

   pre-commit autoupdate

TODO
====

- Use `ruff <https://github.com/astral-sh/ruff>`_


References
==========

- `pre-commit-hooks <https://github.com/pre-commit/pre-commit-hooks>`_