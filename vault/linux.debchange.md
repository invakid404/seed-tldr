---
id: linux.debchange
title: Debchange
desc: ''
updated: 1684034192328
created: 1684034192328
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# debchange

> Tool for maintenance of the debian/changelog file in a Debian source package.
> More information: <https://manpages.debian.org/latest/devscripts/debchange.1.en.html>.

- Add a new version for a non-maintainer upload to the changelog:

`debchange --nmu`

- Add a changelog entry to the current version:

`debchange --append`

- Add a changelog entry to close the bug with specified ID:

`debchange --closes {{bug_id}}`

