---
id: common.trash-cli
title: Trash CLI
desc: ''
updated: 1670483800840
created: 1670483800840
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trash-cli

> A command-line interface to the trashcan APIs.
> More information: <https://github.com/andreafrancia/trash-cli>.

- Trash specific files and directories into the current trashcan:

`trash-put {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Remove specific files from the current trashcan:

`trash-rm {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Empty the current trashcan:

`trash-empty`

- List trashed files and directories in the current trashcan:

`trash-list`

- Restore a specific file or directory by a number from the displayed list from the current trashcan:

`trash-restore`

