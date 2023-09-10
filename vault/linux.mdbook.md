---
id: linux.mdbook
title: Linux
desc: ''
updated: 1694355155142
created: 1694355155142
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mdbook

> Create online books by writing Markdown files.
> More information: <https://rust-lang.github.io/mdBook/>.

- Create an mdbook project in the current directory:

`mdbook init`

- Create an mdbook project in a specific directory:

`mdbook init {{path/to/directory}}`

- Clean the directory with the generated book:

`mdbook clean`

- Serve a book at <http://localhost:3000>, auto build when file changes:

`mdbook serve`

- Watch a set of Markdown files and automatically build when a file is changed:

`mdbook watch`

