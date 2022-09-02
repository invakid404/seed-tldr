---
id: common.mg
title: Mg
desc: ''
updated: 1662128368701
created: 1662128368701
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mg

> A small, fast, and portable text editor based on `emacs`.
> More information: <https://github.com/hboetes/mg>.

- Open a file for editing:

`mg {{path/to/file}}`

- Open a file at a specified line number:

`mg +{{line_number}} {{path/to/file}}`

- Open files in a read-only mode:

`mg -R {{path/to/file1 path/to/file2 ...}}`

- Disable `~` backup files while editing:

`mg -n {{path/to/file}}`

