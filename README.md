Pentaho CPython Plugin
=======================

The Pentaho CPython Project is a plugin for the Pentaho Kettle engine which provides the ability to execute a python script (via the cpython environment) within the context of a transformation.

Building
--------
The Pentaho CPython Plugin is built with Maven.

    $ git clone https://github.com/pentaho-aschurman/pentaho-cpython-plugin
    $ cd pentaho-cpython-plugin
    $ mvn clean install

This will produce a plugin archive in target/pentaho-cpython-plugin-${project.revision}.zip. This archive can then be extracted into your Pentaho Data Integration plugin directory.

Further Reading
---------------
You will need to have python installed on your machine. Either >= 2.7 in the 2.x version of python or 3.x. In addition, the following python packages are required:

pandas (>= 0.7.0)
numpy
scipy
scikit-learn
matplotlib

The Anaconda distribution of python is a simple way to get started (especially for Windows users) as it comes with hundreds of packages pre-installed.

License
-------
Licensed under the Apache License, Version 2.0. See LICENSE.txt for more information.
