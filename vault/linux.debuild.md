---
id: linux.debuild
title: Debuild
desc: ''
updated: 1684034192329
created: 1684034192329
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# debuild

> Tool to build a Debian package from source.
> More information: <https://manpages.debian.org/latest/devscripts/debuild.1.en.html>.

- Build the package in the current directory:

`debuild`

- Build a binary package only:

`debuild -b`

- Do not run lintian after building the package:

`debuild --no-lintian`

