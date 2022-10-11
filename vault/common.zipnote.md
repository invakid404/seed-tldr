---
id: common.zipnote
title: Zipnote
desc: ''
updated: 1665484120467
created: 1665484120467
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipnote

> View, add, or edit a zip archive's comments.
> Files can also be renamed in the zip archive.
> More information: <https://manned.org/zipnote>.

- View the comments on a zip archive:

`zipnote {{path/to/file.zip}}`

- Extract the comments on a zip archive to a file:

`zipnote {{path/to/file.zip}} > {{path/to/file.txt}}`

- Add/Update comments in a zip archive from a file:

`zipnote -w {{path/to/file.zip}} < {{path/to/file.txt}}`

