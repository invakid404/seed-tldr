---
id: common.pip
title: Pip
desc: ''
updated: 1693073888545
created: 1693073888545
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pip

> Python package manager.
> Some subcommands such as `pip install` have their own usage documentation.
> More information: <https://pip.pypa.io>.

- Install a package (see `pip install` for more install examples):

`pip install {{package}}`

- Install a package to the user's directory instead of the system-wide default location:

`pip install --user {{package}}`

- Upgrade a package:

`pip install --upgrade {{package}}`

- Uninstall a package:

`pip uninstall {{package}}`

- Save installed packages to file:

`pip freeze > {{requirements.txt}}`

- Show installed package info:

`pip show {{package}}`

- Install packages from a file:

`pip install --requirement {{requirements.txt}}`

