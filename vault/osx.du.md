---
id: osx.du
title: Du
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
# du

> Disk usage: estimate and summarize file and directory space usage.
> More information: <https://ss64.com/osx/du.html>.

- List the sizes of a directory and any subdirectories, in the given unit (KiB/MiB/GiB):

`du -{{k|m|g}} {{path/to/directory}}`

- List the sizes of a directory and any subdirectories, in human-readable form (i.e. auto-selecting the appropriate unit for each size):

`du -h {{path/to/directory}}`

- Show the size of a single directory, in human-readable units:

`du -sh {{path/to/directory}}`

- List the human-readable sizes of a directory and of all the files and directories within it:

`du -ah {{path/to/directory}}`

- List the human-readable sizes of a directory and any subdirectories, up to N levels deep:

`du -h -d {{2}} {{path/to/directory}}`

- List the human-readable size of all `.jpg` files in subdirectories of the current directory, and show a cumulative total at the end:

`du -ch {{*/*.jpg}}`

