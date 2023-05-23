---
id: common.eslint
title: Eslint
desc: ''
updated: 1684822864523
created: 1684822864523
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eslint

> A pluggable linting utility for JavaScript and JSX.
> More information: <https://eslint.org>.

- Create the ESLint config file:

`eslint --init`

- Lint one or more files:

`eslint {{path/to/file1.js path/to/file2.js ...}}`

- Fix lint issues:

`eslint --fix`

- Lint using the specified config:

`eslint -c {{path/to/config_file}} {{path/to/file1.js path/to/file2.js}}`

