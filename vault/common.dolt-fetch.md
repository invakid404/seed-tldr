---
id: common.dolt-fetch
title: Dolt Fetch
desc: ''
updated: 1665573834333
created: 1665573834333
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt fetch

> Download objects and refs from another repository.
> More information: <https://github.com/dolthub/dolt>.

- Fetch the latest changes from the default remote upstream repository (origin):

`dolt fetch`

- Fetch latest changes from a specific remote upstream repository:

`dolt fetch {{remote_name}}`

- Update branches with the current state of the remote, overwriting any conflicting history:

`dolt fetch -f`

