---
id: common.venv
title: Venv
desc: ''
updated: 1682936285101
created: 1682936285101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# venv

> Create lightweight virtual environments in python.
> More information: <https://docs.python.org/3/library/venv.html>.

- Create a python virtual environment:

` python -m venv {{path/to/virtual_environment}}`

- Activate the virtual environment (Linux and Mac OS):

`source {{path/to/virtual_environment}}/bin/activate`

- Activate the virtual environment (Windows):

`{{path\to\virtual_environment}}\Scripts\activate.bat`

- Deactivate the virtual environment:

`deactivate`

