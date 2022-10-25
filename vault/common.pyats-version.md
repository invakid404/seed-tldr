---
id: common.pyats-version
title: Pyats Version
desc: ''
updated: 1666702579459
created: 1666702579459
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pyats version

> View and upgrade the pyATS installation.
> More information: <https://developer.cisco.com/pyats/>.

- Display version of all packages:

`pyats version check`

- Display outdated packages:

`pyats version check --outdated`

- Update packages to the most recent version:

`pyats version update`

- Update or downgrade packages to a specific version:

`pyats version update {{version}}`

