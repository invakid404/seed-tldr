---
id: common.dfc
title: Dfc
desc: ''
updated: 1656591837442
created: 1656591837442
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dfc

> Gives an overview of the filesystem disk space usage with colors and graphs.
> More information: <https://projects.gw-computing.net/projects/dfc/wiki>.

- Display filesystems and their disk usage in human-readable form with colors and graphs:

`dfc`

- Display all filesystems including pseudo, duplicate and inaccessible filesystems:

`dfc -a`

- Display filesystems without color:

`dfc -c never`

- Display filesystems containing "ext" in the filesystem type:

`dfc -t ext`

