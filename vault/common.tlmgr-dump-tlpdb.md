---
id: common.tlmgr-dump-tlpdb
title: Tlmgr Dump Tlpdb
desc: ''
updated: 1663678087602
created: 1663678087602
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr dump-tlpdb

> Dump the TeX Live package database.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Dump the local package database:

`tlmgr dump-tlpdb --local`

- Dump the remote package database:

`tlmgr dump-tlpdb --remote`

- Dump the local package database as JSON:

`tlmgr dump-tlpdb --local --json`

