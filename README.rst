.. image:: https://travis-ci.org/openopt/copt.svg?branch=master
   :target: https://travis-ci.org/openopt/copt
.. image:: https://coveralls.io/repos/github/openopt/copt/badge.svg?branch=master
   :target: https://coveralls.io/github/openopt/copt?branch=master
.. image:: https://zenodo.org/badge/46262908.svg
   :target: https://zenodo.org/badge/latestdoi/46262908


C-OPT: composite optimization in Python
=======================================

C-OPT is an optimization library written in pure Python that follows the scipy.optimize API.


Documentation
=============

See http://openopt.github.io/copt/


Installation
============

If you already have a working installation of numpy and scipy,
the easiest way to install copt is using ``pip`` ::

    pip install -U copt


Alternatively, you can install the latest development from github with the command::

    pip install git+https://github.com/openopt/copt.git


Citing
======

If this software is useful for your research, please consider citing it as

.. code::

    @article{copt,
      author       = {Fabian Pedregosa},
      title        = {C-OPT: composite optimization in Python},
      year         = 2018,
      DOI          = {10.5281/zenodo.1283339},
      url={http://openopt.github.io/copt/}
    }

Development
===========

The recommended way to work on the development versionis the following:

1. Clone locally the github repo. This can be done with the command::

  git clone https://github.com/openopt/copt.git

This will create a copt directory.

2. Link this directory to your Python interpreter. This can be done by
running the following command from the copt directory created with the
previous step::

  python setup.py develop

Now you can run the tests with `py.test tests/`
