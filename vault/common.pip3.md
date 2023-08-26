---
id: common.pip3
title: Pip3
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
# pip3

> Python package manager.
> More information: <https://pip.pypa.io>.

- Install a package:

`pip3 install {{package}}`

- Install a specific version of a package:

`pip3 install {{package}}=={{version}}`

- Upgrade a package:

`pip3 install --upgrade {{package}}`

- Uninstall a package:

`pip3 uninstall {{package}}`

- Save the list of installed packages to a file:

`pip3 freeze > {{requirements.txt}}`

- Install packages from a file:

`pip3 install --requirement {{requirements.txt}}`

- Show installed package info:

`pip3 show {{package}}`

