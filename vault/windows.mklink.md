---
id: windows.mklink
title: Mklink
desc: ''
updated: 1676881477679
created: 1676881477679
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mklink

> Create symbolic links.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/mklink>.

- Create a symbolic link to a file:

`mklink {{path\to\link_file}} {{path\to\source_file}}`

- Create a symbolic link to a directory:

`mklink /d {{path\to\link_file}} {{path\to\source_directory}}`

- Create a hard link to a file:

`mklink /h {{path\to\link_file}} {{path\to\source_file}}`

- Create a directory junction:

`mklink /j {{path\to\link_file}} {{path\to\source_file}}`

