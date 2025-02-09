---
id: linux.dolphin
title: Dolphin
desc: ''
updated: 1670905392617
created: 1670905392617
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolphin

> KDE's file manager to manage files and directories.
> More information: <https://apps.kde.org/dolphin/>.

- Launch the file manager:

`dolphin`

- Open specific directories:

`dolphin {{path/to/directory1 path/to/directory2 ...}}`

- Open with specific files or directories selected:

`dolphin --select {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Open a new window:

`dolphin --new-window`

- Open specific directories in split view:

`dolphin --split {{path/to/directory1}} {{path/to/directory2}}`

- Launch the daemon (only required to use the DBus interface):

`dolphin --daemon`

- Display help:

`dolphin --help`

