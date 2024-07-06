.. rd_test documentation master file, created by
   sphinx-quickstart on Sat Jul  6 09:58:36 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to rd_test's documentation!
===================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   instll
   support

code bolock
================
.. literalinclude:: main.c
        :language: c
        :caption: mian.c
        :name: main-file
        :emphasize-lines: 9

table example
=============
.. csv-table:: students
        :header: "ID", "name", "age"
        :widths: 15, 20, 15

        1, "fengyaang", 28
        2, "lisi", 22

this *one* word

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
