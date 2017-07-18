About log4cpp
=============

Home: http://log4cpp.sourceforge.net

Package license: LGPL-2.1

Feedstock license: BSD 3-Clause

Summary: C++ library for flexible logging

Log for C++ is a library of C++ classes for flexible logging to files,
syslog and other destinations. It is modeled after the Log for Java library
(http://jakarta.apache.org/log4j/), staying as close to their API as is
reasonable.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/ryanvolz/log4cpp-feedstock.svg?style=shield)](https://circleci.com/gh/ryanvolz/log4cpp-feedstock)
OSX: [![TravisCI](https://travis-ci.org/ryanvolz/log4cpp-feedstock.svg?branch=master)](https://travis-ci.org/ryanvolz/log4cpp-feedstock)
Windows: ![](https://cdn.rawgit.com/conda-forge/conda-smithy/90845bba35bec53edac7a16638aa4d77217a3713/conda_smithy/static/disabled.svg)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/ryanvolz/log4cpp/badges/version.svg)](https://anaconda.org/ryanvolz/log4cpp)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/ryanvolz/log4cpp/badges/downloads.svg)](https://anaconda.org/ryanvolz/log4cpp)

Installing log4cpp
==================

Installing `log4cpp` from the `ryanvolz` channel can be achieved by adding `ryanvolz` to your channels with:

```
conda config --add channels ryanvolz
```

Once the `ryanvolz` channel has been enabled, `log4cpp` can be installed with:

```
conda install log4cpp
```

It is possible to list all of the versions of `log4cpp` available on your platform with:

```
conda search log4cpp --channel ryanvolz
```




Updating log4cpp-feedstock
==========================

If you would like to improve the log4cpp recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ryanvolz` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ryanvolz` channel.
Note that all branches in the conda-forge/log4cpp-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
