---
id: common.opam
title: Opam
desc: ''
updated: 1693073888536
created: 1693073888536
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# opam

> OCaml Package Manager.
> Manage OCaml compilers, tools and libraries.
> More information: <https://opam.ocaml.org/>.

- Initialize opam for first use:

`opam init`

- Search for packages:

`opam search {{query}}`

- Install a package and all of its dependencies:

`opam install {{package}}`

- Display detailed information about a package:

`opam show {{package}}`

- List all installed packages:

`opam list`

- Update the local package database:

`opam update`

- Upgrade all installed packages:

`opam upgrade`

- Display all commands:

`opam help`

