========================
include
========================


An example of including non-code files in a package.


Project structure
=================

::

    include
    ├── AUTHORS.rst
    ├── CHANGELOG.rst
    ├── LICENSE.txt
    ├── Makefile
    ├── README.rst
    ├── docs
    │   ├── Makefile
    │   ├── _static
    │   ├── authors.rst
    │   ├── changelog.rst
    │   ├── conf.py
    │   ├── index.rst
    │   └── license.rst
    ├── requirements.txt
    ├── setup.cfg
    ├── setup.py
    ├── src
    │   └── include
    │       ├── __init__.py
    │       └── include.py
    └── tests
        ├── conftest.py
        └── test_include.py


Note
====

This project has been set up using PyScaffold 3.1 and Cookiecutter 1.6.

For details and usage information on PyScaffold, see https://pyscaffold.org/.

For details and usage information on Cookiecutter, see https://cookiecutter.readthedocs.io/.
