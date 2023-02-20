---
id: osx.ditto
title: Ditto
desc: ''
updated: 1676877466489
created: 1676877466489
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ditto

> Copy files and directories.
> More information: <https://ss64.com/osx/ditto.html>.

- Overwrite contents of destination directory with contents of source directory:

`ditto {{path/to/source_directory}} {{path/to/destination_directory}}`

- Print a line to the Terminal window for every file that's being copied:

`ditto -V {{path/to/source_directory}} {{path/to/destination_directory}}`

- Copy a given file or directory, while retaining the original file permissions:

`ditto -rsrc {{path/to/source_directory}} {{path/to/destination_directory}}`

