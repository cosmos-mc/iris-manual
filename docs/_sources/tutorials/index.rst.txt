Tutorials
=========

Not sure where to begin? Take a look at :doc:`/user/getting_started`.

Quick Starts
------------

.. toctree::
    :maxdepth: 1


Installation
------------

.. toctree::
    :maxdepth: 1


Data In/Out
-----------

.. toctree::
    :maxdepth: 1


.. _tutorials_analytics:

Data Analysis
-------------

.. toctree::
    :maxdepth: 1



Security
--------

.. toctree::
    :maxdepth: 1


Indexing and Queries
--------------------

.. toctree::
    :maxdepth: 1



.. _tutorial_versions:

About Tutorial Versions
-----------------------

The tutorials listed in this manual can be obtained from GitHub, by
cloning the `geomesa-tutorials`_ project:

.. code-block:: bash

    $ git clone https://github.com/geomesa/geomesa-tutorials.git
    $ cd geomesa-tutorials

Keep in mind that you should download or checkout the release version corresponding to the GeoMesa version
you are using:

.. code-block:: bash

    $ git checkout tags/geomesa-tutorials-$TUTORIAL_VERSION

In general, the major, minor, and patch version numbers of the
tutorials release will match the corresponding numbers of the
GeoMesa version. The tutorials version contains a fourth digit
number permitting multiple releases per GeoMesa release.

You may also see the releases available, and download them directly from the `geomesa-tutorials releases page`_.

.. _geomesa-tutorials: https://github.com/geomesa/geomesa-tutorials/

.. _geomesa-tutorials releases page: https://github.com/geomesa/geomesa-tutorials/releases

Hadoop Version
^^^^^^^^^^^^^^

Most of the tutorials encourage you to update the ``pom.xml``
to match the versions of the services you are using (Hadoop,
ZooKeeper, Accumulo, etc.) However, there may be issues when
incrementing the Hadoop version to 2.6 or above, which can result
in Apache Curator version conflicts. Leaving the
Hadoop version set to 2.2 in the tutorials ``pom.xml`` will work
with all subsequent Hadoop 2.X releases.
