<!--
# -*- mode: jinja -*-
-->

About mcerp
===========

Home: https://github.com/tisimst/mcerp

Package license: BSD-3-Clause

Feedstock license: BSD 3-Clause

Summary: Real-time latin-hypercube-sampling-based Monte Carlo Error Propagation

`mcerp` is a stochastic calculator for [Monte Carlo methods](http://en.wikipedia.org/wiki/Monte_Carlo_method) that uses
[latin-hypercube sampling](http://en.wikipedia.org/wiki/Latin_hypercube_sampling)
to perform non-order specific [error propagation](http://en.wikipedia.org/wiki/Propagation_of_uncertainty)
(or uncertainty analysis).

With this package you can **easily** and **transparently** track the effects
of uncertainty through mathematical calculations. Advanced mathematical
functions, similar to those in the standard [`math`](http://docs.python.org/library/math.html)
module, and statistical functions like those in the [`scipy.stats`](http://docs.scipy.org/doc/scipy/reference/stats.html)
module, can also be evaluated directly.

If you are familiar with Excel-based risk analysis programs like *@Risk*,
*Crystal Ball*, *ModelRisk*, etc., this package **will work wonders** for you
(and probably even be faster!) and give you more modelling flexibility with
the powerful Python language. This package also *doesn't cost a penny*,
compared to those commercial packages which cost *thousands of dollars* for a
single-seat license. Feel free to copy and redistribute this package as much
as you desire!


Current build status
====================

All platforms:
[![noarch](https://img.shields.io/circleci/project/github/conda-forge/mcerp-feedstock/master.svg?label=noarch)](https://circleci.com/gh/conda-forge/mcerp-feedstock)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mcerp-green.svg)](https://anaconda.org/conda-forge/mcerp) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mcerp.svg)](https://anaconda.org/conda-forge/mcerp) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mcerp.svg)](https://anaconda.org/conda-forge/mcerp) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mcerp.svg)](https://anaconda.org/conda-forge/mcerp) |

Installing mcerp
================

Installing `mcerp` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `mcerp` can be installed with:

```
conda install mcerp
```

It is possible to list all of the versions of `mcerp` available on your platform with:

```
conda search mcerp --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating mcerp-feedstock
========================

If you would like to improve the mcerp recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/mcerp-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@chrisburr](https://github.com/chrisburr/)

