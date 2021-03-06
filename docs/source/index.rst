.. Qfactor documentation master file, created by
   sphinx-quickstart on Tue Jul  5 15:45:48 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Alphalens
=========

Alphalens is a Python Library for performance analysis of predictive
(alpha) stock factors. Alphalens works great with the
`Zipline <http://zipline.io/>`__ open source backtesting library, and
`Pyfolio <https://github.com/quantopian/pyfolio>`__ which provides
performance and risk analysis of financial portfolios.

The main function of Alphalens is to surface the most relevant statistics
and plots about an alpha factor, including:

-  Information Coefficient Analysis
-  Returns Analysis
-  Turnover Analysis
-  Sector Analysis

Getting started
---------------

With a signal and pricing data creating a factor "tear sheet" is just:

.. code:: python

    import alphalens

    alphalens.tears.create_factor_tear_sheet(my_factor, pricing)


Learn more
----------

Check out the `example notebooks <https://github.com/quantopian/qfactor/tree/master/examples>`__ for more on how to read and use
the factor tear sheet.

Installation
------------

::

    pip install alphalens

Alphalens depends on:

-  `matplotlib <https://github.com/matplotlib/matplotlib>`__
-  `numpy <https://github.com/numpy/numpy>`__
-  `pandas <https://github.com/pydata/pandas>`__
-  `scipy <https://github.com/scipy/scipy>`__
-  `seaborn <https://github.com/mwaskom/seaborn>`__
-  `statsmodels <https://github.com/statsmodels/statsmodels>`__

Usage
-----

A good way to get started is to run the examples in a `Jupyter
notebook <http://jupyter.org/>`__.

To get set up with an example, you can:

Run a Jupyter notebook server via:

.. code:: bash

    jupyter notebook

From the notebook list page(usually found at
``http://localhost:8888/``), navigate over to the examples directory,
and open any file with a .ipynb extension.

Execute the code in a notebook cell by clicking on it and hitting
Shift+Enter.

Questions?
----------

If you find a bug, feel free to open an issue on our `github
tracker <https://github.com/quantopian/alphalens/issues>`__.

Contribute
----------

If you want to contribute, a great place to start would be the
`help-wanted
issues <https://github.com/quantopian/alphalens/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22>`__.

Credits
-------

-  `Andrew Campbell <https://github.com/a-campbell>`__
-  `James Christopher <https://github.com/jameschristopher>`__
-  `Thomas Wiecki <https://github.com/twiecki>`__
-  `Jonathan Larkin <https://github.com/marketneutral>`__
-  Jessica Stauth (jstauth@quantopian.com)

Example Tear Sheet
------------------

Example factor courtesy of `ExtractAlpha <http://extractalpha.com/>`_

.. image:: examples/table_tear.png
.. image:: examples/returns_tear.png
.. image:: examples/ic_tear.png
.. image:: examples/sector_tear.png
    :alt:

API
---

Information on a specific functions, classes, or methods.

- :mod:`alphalens.tears`
- :mod:`alphalens.performance`
- :mod:`alphalens.plotting`
- :mod:`alphalens.utils`
