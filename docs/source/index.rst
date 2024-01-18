.. DSBench documentation master file, created by
   sphinx-quickstart on Thu Jan 18 00:07:13 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

DSBench
===================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

This small library provides a decorator function that benchmarks functions.


Installation
===================================

.. code-block:: bash

    pip install dsbench


Usage
===================================

.. code-block:: python

    import dsbench

    @dsbench.benchmark(name="Some Function")
    def some_function():
        return 98

    my_function()

    # prints:
    # Some Function:
    #   Time: 0:00:00.000002
    #   Result: 98

API
===================================

.. autofunction:: dsbench.benchmark

Links
===================================

`PyPI <https://pypi.org/project/dsbench/>`_ | `GitHub <https://github.com/DemonicSavage/dsbench>`_
