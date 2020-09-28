About postgresql-split
======================

Home: 

Package license: 

Feedstock license: BSD-3-Clause

Summary: The postgres runtime libraries and utilities (not the server itself)



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/postgresql-feedstock?branchName=master&jobName=win&configuration=win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-libpq-green.svg)](https://anaconda.org/ramonaoptics/libpq) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/libpq.svg)](https://anaconda.org/ramonaoptics/libpq) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/libpq.svg)](https://anaconda.org/ramonaoptics/libpq) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/libpq.svg)](https://anaconda.org/ramonaoptics/libpq) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-postgresql-green.svg)](https://anaconda.org/ramonaoptics/postgresql) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/postgresql.svg)](https://anaconda.org/ramonaoptics/postgresql) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/postgresql.svg)](https://anaconda.org/ramonaoptics/postgresql) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/postgresql.svg)](https://anaconda.org/ramonaoptics/postgresql) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-postgresql--plpython-green.svg)](https://anaconda.org/ramonaoptics/postgresql-plpython) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/postgresql-plpython.svg)](https://anaconda.org/ramonaoptics/postgresql-plpython) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/postgresql-plpython.svg)](https://anaconda.org/ramonaoptics/postgresql-plpython) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/postgresql-plpython.svg)](https://anaconda.org/ramonaoptics/postgresql-plpython) |

Installing postgresql-split
===========================

Installing `postgresql-split` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
```

Once the `ramonaoptics` channel has been enabled, `libpq, postgresql, postgresql-plpython` can be installed with:

```
conda install libpq postgresql postgresql-plpython
```

It is possible to list all of the versions of `libpq` available on your platform with:

```
conda search libpq --channel ramonaoptics
```




Updating postgresql-split-feedstock
===================================

If you would like to improve the postgresql-split recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/postgresql-split-feedstock are
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

* [@gillins](https://github.com/gillins/)
* [@mariusvniekerk](https://github.com/mariusvniekerk/)
* [@msarahan](https://github.com/msarahan/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@sodre](https://github.com/sodre/)

