---
id: common.pyenv
title: Pyenv
desc: ''
updated: 1660130270396
created: 1660130270396
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pyenv

> Switch between multiple versions of Python easily.
> More information: <https://github.com/pyenv/pyenv>.

- List all available commands:

`pyenv commands`

- List all Python versions under the `${PYENV_ROOT}/versions` directory:

`pyenv versions`

- List all Python versions that can be installed from upstream:

`pyenv install --list`

- Install a Python version under the `${PYENV_ROOT}/versions` directory:

`pyenv install {{2.7.10}}`

- Uninstall a Python version under the `${PYENV_ROOT}/versions` directory:

`pyenv uninstall {{2.7.10}}`

- Set Python version to be used globally in the current machine:

`pyenv global {{2.7.10}}`

- Set Python version to be used in the current directory and all directories below it:

`pyenv local {{2.7.10}}`

