---
id: common.mamba-repoquery
title: Mamba Repoquery
desc: ''
updated: 1666197757077
created: 1666197757077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mamba repoquery

> Efficiently query conda and mamba package repositories and package dependencies.
> More information: <https://mamba.readthedocs.io/en/latest/user_guide/mamba.html#repoquery>.

- Search for all available versions of a particular package:

`mamba repoquery search {{package_name}}`

- Search for all packages satisfying specific constraints:

`mamba repoquery search {{sphinx<5}}`

- List the dependencies of a package installed in the currently activated environment, in a tree format:

`mamba repoquery depends --tree {{scipy}}`

- Print packages in the current environment that require a particular package to be installed (i.e. inverse of `depends`):

`mamba repoquery whoneeds {{ipython}}`

