---
id: common.unison
title: Unison
desc: ''
updated: 1656591837586
created: 1656591837586
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unison

> Bidirectional file synchronisation tool.
> More information: <https://www.cis.upenn.edu/~bcpierce/unison/download/releases/stable/unison-manual.html>.

- Sync two directories (creates log first time these two directories are synchronized):

`unison {{path/to/directory_1}} {{path/to/directory_2}}`

- Automatically accept the (non-conflicting) defaults:

`unison {{path/to/directory_1}} {{path/to/directory_2}} -auto`

- Ignore some files using a pattern:

`unison {{path/to/directory_1}} {{path/to/directory_2}} -ignore {{pattern}}`

- Show documentation:

`unison -doc {{topics}}`

