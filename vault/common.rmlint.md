---
id: common.rmlint
title: Rmlint
desc: ''
updated: 1666111239014
created: 1666111239014
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmlint

> Identify duplicate files or directories, and other filesystem issues.
> More information: <https://rmlint.readthedocs.io/en/latest/rmlint.1.html>.

- Check a directory for duplicates, empty files, and other issues:

`rmlint {{path/to/directory}}`

- Delete duplicate files found by an execution of `rmlint`:

`./rmlint.sh`

- Find duplicate directory trees:

`rmlint --merge-directories {{path/to/directory}}`

- Mark files at lower path [d]epth as originals:

`rmlint --rank-by={{d}} {{path/to/directory}}`

- Mark files with shortest name [l]ength as originals:

`rmlint --rank-by={{l}} {{path/to/directory}}`

- Find only duplicates that have the same filename in addition to the same contents:

`rmlint --match-basename {{path/to/directory}}`

- Find all duplicates with the same extension:

`rmlint --match-extension {{path/to/directory}}`

