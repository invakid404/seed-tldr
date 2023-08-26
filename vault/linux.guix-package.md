---
id: linux.guix-package
title: Guix Package
desc: ''
updated: 1693073888635
created: 1693073888635
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# guix package

> Install, upgrade and remove Guix packages, or rollback to previous configurations.
> More information: <https://guix.gnu.org/manual/html_node/Invoking-guix-package.html>.

- Install a new package:

`guix package -i {{package}}`

- Remove a package:

`guix package -r {{package}}`

- Search the package database for a regular expression:

`guix package -s "{{search_pattern}}"`

- List installed packages:

`guix package -I`

- List generations:

`guix package -l`

- Roll back to the previous generation:

`guix package --roll-back`

