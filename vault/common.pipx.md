---
id: common.pipx
title: Pipx
desc: ''
updated: 1683040744502
created: 1683040744502
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pipx

> Install and run Python applications in isolated environments.
> More information: <https://github.com/pypa/pipx>.

- Run an app in a temporary virtual environment:

`pipx run {{pycowsay}} {{moo}}`

- Install a package in a virtual environment and add entry points to path:

`pipx install {{package}}`

- List installed packages:

`pipx list`

- Run an app in a temporary virtual environment with a package name different from the executable:

`pipx run --spec {{httpx-cli}} {{httpx}} {{http://www.github.com}}`

- Inject dependencies into an existing virtual environment:

`pipx inject {{package}} {{dependency1 dependency2 ...}}`

- Install a package in a virtual environment with pip arguments:

`pipx install --pip-args='{{pip-args}}' {{package}}`

