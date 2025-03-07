.. Trading212 Connector documentation master file, created by
   sphinx-quickstart on Fri Mar  7 15:49:22 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Trading212 Connector documentation
==================================

A simple http wrapper for the trading212 trading platform ( see https://t212public-api-docs.redoc.ly )


Installation
------------
I recommend using a virtual env.

From git

.. code-block:: bash

   $ git clone git@github.com:niall-oc/trading212.git
   $ cd trading212
   $ pip install .
   $ cd src
   $ python
   >>> from trading212 import Client
   >>> c = Client('YOUR_API_KEY')
   >>> c = Client('YOUR_API_KEY', domain='demo.trading212.com', version='v0')

From pypi

.. code-block:: bash

   $ pip install trading212-connector
   $ python
   >>> from trading212 import Client
   >>> c = Client('YOUR_API_KEY')
   >>> c = Client('YOUR_API_KEY', domain='demo.trading212.com', version='v0')


The guides below provide code snippets. For a full spec of the API click on the ```src``` link at the bottom of the table of contents.


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   modules

