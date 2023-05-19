---
id: common.tslint
title: Tslint
desc: ''
updated: 1684520364312
created: 1684520364312
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tslint

> A pluggable linting utility for TypeScript.
> More information: <https://palantir.github.io/tslint>.

- Create TSLint config:

`tslint --init`

- Lint on a given set of files:

`tslint {{path/to/file1.js path/to/file2.js ...}}`

- Fix lint issues:

`tslint --fix`

- Lint with the config file in the project root:

`tslint --project {{path/to/project_root}}`

