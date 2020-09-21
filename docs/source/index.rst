.. DDS documentation documentation master file, created by
   sphinx-quickstart on Thu Sep 17 17:37:20 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to DDS's documentation!
=============================================


Code block example
------------------

This section will be deleted or hidden later on but just help you guide how to use code block in Sphinx so that we can effectively visualise code/shell commands or etc. 

* **Getting started**:
  :doc:`/code-block-examples`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Code block example

   /code-block-examples

Sub-menu examples
-----------------
This is a simple example how to create sub menus. When you create a sub menu, please follow the file name convention such that ``subMenuXX`` where ``XX`` indicates the sequence number of sub-menu. In addition, you can place a newly created sub menu file (e.g., ``subMenu03.rst``) under ``docs/source/subMenu``.

* **Sub-menu**:
  :doc:`/subMenu/subMenu01` |
  :doc:`/subMenu/subMenu02` 

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Sub Menus

   /subMenu/subMenu01
   /subMenu/subMenu02

Contacts
--------
If you have any questions in related to this project, please let us know. 

* **Contact**:
  :doc:`/contacts/license` |
  :doc:`/contacts/help` 

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Contact

   license
   help

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
