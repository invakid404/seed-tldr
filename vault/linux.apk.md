---
id: linux.apk
title: Apk
desc: ''
updated: 1666284000494
created: 1666284000494
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apk

> Alpine Linux package management tool.
> More information: <https://wiki.alpinelinux.org/wiki/Alpine_Linux_package_management>.

- Update repository indexes from all remote repositories:

`apk update`

- Install a new package:

`apk add {{package}}`

- Remove a package:

`apk del {{package}}`

- Repair a package or upgrade it without modifying main dependencies:

`apk fix {{package}}`

- Search for a package via keywords:

`apk search {{keywords}}`

- Display information about a specific package:

`apk info {{package}}`

