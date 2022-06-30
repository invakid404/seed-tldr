---
id: common.just
title: Just
desc: ''
updated: 1656591837505
created: 1656591837505
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# just

> Save and run project-specific commands.
> More information: <https://github.com/casey/just>.

- Run a recipe specified in the justfile:

`just {{recipe}}`

- Initialize new justfile in project root:

`just --init`

- Edit justfile in the default editor:

`just -e`

- List available recipes in the justfile:

`just -l`

- Print justfile:

`just --dump`

