About pet-neighbors-convert-feedstock
=====================================

Feedstock license: [BSD-3-Clause](https://github.com/abmazitov/pet-neighbors-convert-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/lab-cosmo/pet-neighbors-convert

Package license: BSD-3-Clause

Summary: A C++ PyTorch extension for neiborslist reordering in PET

Documentation: https://github.com/lab-cosmo/pet-neighbors-convert

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pet--neighbors--convert-green.svg)](https://anaconda.org/metatensor/pet-neighbors-convert) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/pet-neighbors-convert.svg)](https://anaconda.org/metatensor/pet-neighbors-convert) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/pet-neighbors-convert.svg)](https://anaconda.org/metatensor/pet-neighbors-convert) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/pet-neighbors-convert.svg)](https://anaconda.org/metatensor/pet-neighbors-convert) |

Installing pet-neighbors-convert
================================

Installing `pet-neighbors-convert` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `pet-neighbors-convert` can be installed with `conda`:

```
conda install pet-neighbors-convert
```

or with `mamba`:

```
mamba install pet-neighbors-convert
```

It is possible to list all of the versions of `pet-neighbors-convert` available on your platform with `conda`:

```
conda search pet-neighbors-convert --channel metatensor
```

or with `mamba`:

```
mamba search pet-neighbors-convert --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search pet-neighbors-convert --channel metatensor

# List packages depending on `pet-neighbors-convert`:
mamba repoquery whoneeds pet-neighbors-convert --channel metatensor

# List dependencies of `pet-neighbors-convert`:
mamba repoquery depends pet-neighbors-convert --channel metatensor
```




Updating pet-neighbors-convert-feedstock
========================================

If you would like to improve the pet-neighbors-convert recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the abmazitov/pet-neighbors-convert-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@PicoCentauri](https://github.com/PicoCentauri/)
* [@abmazitov](https://github.com/abmazitov/)

