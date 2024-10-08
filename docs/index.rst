Welcome to listwiz's documentation!
===================================

In this documentation you will find information about the `listwiz` project.
`listwiz` allows you to handle lists: sort them, find the longest increasing
streaks, and identify the most frequently occurring elements::

    >>> import listwiz as lwz
    >>> unsorted_list = [2, 4, 1, 3, 5, 10, 7, 8, 9, 6]
    >>> sorted_list = lwz.sorting.merge_sort(unsorted_list)
    >>> sorted_list
    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

Table of Contents
=================

.. toctree::
   :maxdepth: 2

   installation/index.rst
   contributing/index.rst
   api.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`