---
id: common.pipenv
title: Pipenv
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
# pipenv

> Simple and unified Python development workflow.
> Manages packages and the virtual environment for a project.
> More information: <https://pypi.org/project/pipenv>.

- Create a new project:

`pipenv`

- Create a new project using Python 3:

`pipenv --three`

- Install a package:

`pipenv install {{package}}`

- Install all the dependencies for a project:

`pipenv install`

- Install all the dependencies for a project (including dev packages):

`pipenv install --dev`

- Uninstall a package:

`pipenv uninstall {{package}}`

- Start a shell within the created virtual environment:

`pipenv shell`

- Generate a `requirements.txt` (list of dependencies) for a project:

`pipenv lock --requirements`

