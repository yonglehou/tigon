.. :author: Cask Data, Inc.
   :description: Tigon Examples
   :copyright: Copyright © 2014 Cask Data, Inc.

============================================
Tigon Examples and Reference Applications
============================================

.. toctree::
   :maxdepth: 1
   :titlesonly:

   Hello World <hello-world>
   Twitter Analytics <twitter-analytics>
   SQL Join Flow <sql-join-flow>
   TigonSQL <tigon-sql>

Examples
========

These examples are included in the `source download <getting-started.html#download>`__ 
in the ``tigon-examples`` directory.

- `Hello World Example <hello-world.html>`__

  .. include:: hello-world.rst
     :start-line: 5
     :end-before: Building the JAR

- `Twitter Analytics Example <twitter-analytics.html>`__

  .. include:: twitter-analytics.rst
     :start-line: 5
     :end-before: Twitter Configuration

- `SQL Join Flow Example <sql-join-flow.html>`__

  .. include:: sql-join-flow.rst
     :start-line: 5
     :end-before: Flow Runtime Arguments

Reference Applications
======================

Reference applications built with Tigon are included in the 
`tigon-apps repository <https://github.com/caskdata/tigon-apps>`__ at 
`GitHub: <https://github.com/caskdata>`__

- `AdNetworkFlow: <https://github.com/caskdata/tigon-apps/tree/develop/AdNetworkFlow>`__
  Demonstrates using Tigon to write a realtime bidding (RTB) advertisement framework.

- `ClickStreamFlow: <https://github.com/caskdata/tigon-apps/tree/develop/ClickStreamFlow>`__
  Demonstrates using Tigon SQL to join 2 data streams. In this example, a view event data
  stream and a click event data stream are joined to generate meta information for each
  click event. Click events are filtered on the basis of conditions specified in a SQL query.

Where to Go Next
================

Now that you're seen an example demonstrating Tigon, take a look at:

- :doc:`/apis/index`, which includes the Java and TigonSQL APIs of Tigon.
