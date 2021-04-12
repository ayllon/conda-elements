About elements
==============

Home: https://github.com/astrorama/Elements.git

Package license: LGPL

Feedstock license: [BSD-3-Clause](https://github.com/astrorama/elements-feedstock/blob/master/LICENSE.txt)

Summary: Elements is a C++/Python build framework. It helps to organize the software into modules which are gathered into projects.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
            <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=1&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/elements-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-elements-green.svg)](https://anaconda.org/astrorama/elements) | [![Conda Downloads](https://img.shields.io/conda/dn/astrorama/elements.svg)](https://anaconda.org/astrorama/elements) | [![Conda Version](https://img.shields.io/conda/vn/astrorama/elements.svg)](https://anaconda.org/astrorama/elements) | [![Conda Platforms](https://img.shields.io/conda/pn/astrorama/elements.svg)](https://anaconda.org/astrorama/elements) |

Installing elements
===================

Installing `elements` from the `astrorama` channel can be achieved by adding `astrorama` to your channels with:

```
conda config --add channels astrorama
conda config --set channel_priority strict
```

Once the `astrorama` channel has been enabled, `elements` can be installed with:

```
conda install elements
```

It is possible to list all of the versions of `elements` available on your platform with:

```
conda search elements --channel astrorama
```




Updating elements-feedstock
===========================

If you would like to improve the elements recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`astrorama` channel, whereupon the built conda packages will be available for
everybody to install and use from the `astrorama` channel.
Note that all branches in the astrorama/elements-feedstock are
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


