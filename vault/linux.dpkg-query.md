---
id: linux.dpkg-query
title: Dpkg Query
desc: ''
updated: 1658341531828
created: 1658341531828
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dpkg-query

> A tool that shows information about installed packages.
> More information: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- List all installed packages:

`dpkg-query --list`

- List installed packages matching a pattern:

`dpkg-query --list '{{libc6*}}'`

- List all files installed by a package:

`dpkg-query --listfiles {{libc6}}`

- Show information about a package:

`dpkg-query --status {{libc6}}`

- Search for packages that own files matching a pattern:

`dpkg-query --search {{/etc/ld.so.conf.d}}`

