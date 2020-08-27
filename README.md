About uwsgi
===========

Home: https://github.com/unbit/uwsgi

Package license: GPL-2.0

Feedstock license: BSD-3-Clause

Summary: The uWSGI project aims at developing a full stack for building hosting
services. Application servers (for various programming languages and
protocols), proxies, process managers and monitors are all implemented.




Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=118&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/uwsgi-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.6</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=118&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/uwsgi-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.6" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.7</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=118&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/uwsgi-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.7" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=118&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/uwsgi-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.8" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-uwsgi-green.svg)](https://anaconda.org/nsls2forge/uwsgi) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/uwsgi.svg)](https://anaconda.org/nsls2forge/uwsgi) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/uwsgi.svg)](https://anaconda.org/nsls2forge/uwsgi) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/uwsgi.svg)](https://anaconda.org/nsls2forge/uwsgi) |

Installing uwsgi
================

Installing `uwsgi` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `uwsgi` can be installed with:

```
conda install uwsgi
```

It is possible to list all of the versions of `uwsgi` available on your platform with:

```
conda search uwsgi --channel nsls2forge
```




Updating uwsgi-feedstock
========================

If you would like to improve the uwsgi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/uwsgi-feedstock are
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


