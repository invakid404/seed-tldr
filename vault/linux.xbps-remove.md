---
id: linux.xbps-remove
title: Xbps Remove
desc: ''
updated: 1689488527979
created: 1689488527979
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xbps-remove

> XBPS utility to remove packages.
> See also: `xbps`.
> More information: <https://man.voidlinux.org/xbps-remove.1>.

- Remove a package:

`xbps-remove {{package}}`

- Remove a package and its dependencies:

`xbps-remove --recursive {{package}}`

- Remove orphan packages (installed as dependencies but no longer required by any package):

`xbps-remove --remove-orphans`

- Remove obsolete packages from the cache:

`xbps-remove --clean-cache`

