---
id: osx.setfile
title: Setfile
desc: ''
updated: 1669555468885
created: 1669555468885
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# setfile

> Sets file attributes on files in an HFS+ directory.
> More information: <https://ss64.com/osx/setfile.html>.

- Set creation date for specific files:

`setfile -d "{{MM/DD/YYYY HH:MM:SS}}" {{path/to/file1 path/to/file2 ...}}`

- Set modification date for specific files:

`setfile -m "{{MM/DD/YYYY HH:MM:SS}}" {{path/to/file1 path/to/file2 ...}}`

- Set modification date for symlink file (not to linked file itself):

`setfile -P -m "{{MM/DD/YYYY HH:MM:SS}}" {{path/to/file1 path/to/file2 ...}}`

