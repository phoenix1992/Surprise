[![GitHub version](https://badge.fury.io/gh/Niourf%2Frecsys.svg)](https://badge.fury.io/gh/Niourf%2Frecsys)
[![Documentation Status](https://readthedocs.org/projects/recsys/badge/?version=latest)](http://recsys.readthedocs.io/en/latest/?badge=latest)
[![Build Status](https://travis-ci.org/Niourf/RecSys.svg?branch=master)](https://travis-ci.org/Niourf/RecSys)
[![python_versions](https://img.shields.io/badge/python-2.7%2C%203.4%2C%203.5-blue.svg)]
(https://pypi.python.org/pypi/recsys/)
[![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://github.com/Niourf/RecSys/blob/master/LICENSE.md)


RecSys
======

author: Nicolas Hug

Overview
--------

RecSys is an open source Python package that provides with tools to build and
evaluate the performance of many recommender system prediction algorithms. Its
goal is to make life easy(-ier) for reseachers and students who want to play
around with new recommender algorithm ideas.

A strong emphasis is laid on
[documentation](http://recsys.readthedocs.io/en/latest/index.html), which we
have tried to make as clear and precise as possible by pointing out every
detail of the algorithms, in order for the practitioner to have perfect
control over his experiments.

Features
--------

- [Dataset
  handling](http://recsys.readthedocs.io/en/latest/getting_started.html) is made easy.
- Various ready-to-use [prediction
  algorithms](http://recsys.readthedocs.io/en/latest/prediction_algorithms.html).
- Easy to implement [new algorithm
  ideas](http://recsys.readthedocs.io/en/latest/building_custom_algo.html).
- Evaluate,
  [analyse](http://nbviewer.jupyter.org/github/Niourf/RecSys/tree/master/examples/notebooks/KNNBasic_analysis.ipynb/)
  and
  [compare](http://nbviewer.jupyter.org/github/Niourf/RecSys/tree/master/examples/notebooks/Compare.ipynb/) the algorithms performance.

Installation / Usage
--------------------

Please, use a [virtual env](
http://docs.python-guide.org/en/latest/dev/virtualenvs/)

To install from [PyPI](https://pypi.python.org/pypi/recsys/), use pip
(recommended):

    $ pip install recsys

Or clone the repo and build from the sources (you'll need Cython and numpy
first):

    $ git clone https://github.com/Niourf/recsys.git
    $ python setup.py install


Documentation, Getting Started
------------------------------

The documentation with many usage examples is available
[online](http://recsys.readthedocs.io/en/latest/index.html) on ReadTheDocs.

License
-------

This project is licensed under the GPLv3 license - see the LICENSE.md file for
details.

Acknowledgements:
----------------

- [Pierre-François Gimenez](https://github.com/PFgimenez), for his valuable
  insights on software design.

Contributing
------------

Any kind of feedback would be greatly appreciated (software design,
documentation, improvement ideas, spelling, etc...). Please feel free to
contirbute!
