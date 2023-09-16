About rust-split-feedstock
==========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/rust-feedstock/blob/main/LICENSE.txt)

Home: https://www.rust-lang.org

Package license: MIT

Summary: Rust is a systems programming language that runs blazingly fast, prevents segfaults, and guarantees thread safety.
This package provides the compiler (rustc) and the documentation utilities rustdoc.


Development: https://doc.rust-lang.org/std/

Documentation: https://www.rust-lang.org/en-US/documentation.html

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4321&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/rust-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_armv7l</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4321&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/rust-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_armv7l_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-rust-green.svg)](https://anaconda.org/e8035669acarmv7/rust) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/rust.svg)](https://anaconda.org/e8035669acarmv7/rust) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/rust.svg)](https://anaconda.org/e8035669acarmv7/rust) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/rust.svg)](https://anaconda.org/e8035669acarmv7/rust) |

Installing rust-split
=====================

Installing `rust-split` from the `e8035669acarmv7` channel can be achieved by adding `e8035669acarmv7` to your channels with:

```
conda config --add channels e8035669acarmv7
conda config --set channel_priority strict
```

Once the `e8035669acarmv7` channel has been enabled, `rust` can be installed with `conda`:

```
conda install rust
```

or with `mamba`:

```
mamba install rust
```

It is possible to list all of the versions of `rust` available on your platform with `conda`:

```
conda search rust --channel e8035669acarmv7
```

or with `mamba`:

```
mamba search rust --channel e8035669acarmv7
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search rust --channel e8035669acarmv7

# List packages depending on `rust`:
mamba repoquery whoneeds rust --channel e8035669acarmv7

# List dependencies of `rust`:
mamba repoquery depends rust --channel e8035669acarmv7
```




Updating rust-split-feedstock
=============================

If you would like to improve the rust-split recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`e8035669acarmv7` channel, whereupon the built conda packages will be available for
everybody to install and use from the `e8035669acarmv7` channel.
Note that all branches in the conda-forge/rust-split-feedstock are
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

* [@abhi18av](https://github.com/abhi18av/)
* [@dlaehnemann](https://github.com/dlaehnemann/)
* [@isuruf](https://github.com/isuruf/)
* [@johanneskoester](https://github.com/johanneskoester/)
* [@mbargull](https://github.com/mbargull/)
* [@pkgw](https://github.com/pkgw/)
* [@timkpaine](https://github.com/timkpaine/)
* [@xhochy](https://github.com/xhochy/)

