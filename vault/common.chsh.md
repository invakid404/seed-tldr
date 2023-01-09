---
id: common.chsh
title: Chsh
desc: ''
updated: 1673284741478
created: 1673284741478
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chsh

> Change user's login shell.
> More information: <https://manned.org/chsh>.

- Set a specific login shell for the current user interactively:

`chsh`

- Set a specific login [s]hell for the current user:

`chsh -s {{path/to/shell}}`

- Set a login [s]hell for a specific user:

`chsh -s {{path/to/shell}} {{username}}`

- [l]ist available shells:

`chsh -l`

