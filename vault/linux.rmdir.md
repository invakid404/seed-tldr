---
id: linux.rmdir
title: Rmdir
desc: ''
updated: 1673108585002
created: 1673108585002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmdir

> Remove directories without files.
> See also: `rm`.
> More information: <https://www.gnu.org/software/coreutils/rmdir>.

- Remove specific directories:

`rmdir {{path/to/directory1 path/to/directory2 ...}}`

- Remove specific nested directories recursively:

`rmdir --parents {{path/to/directory1 path/to/directory2 ...}}`

