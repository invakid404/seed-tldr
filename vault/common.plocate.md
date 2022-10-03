---
id: common.plocate
title: Plocate
desc: ''
updated: 1664832190256
created: 1664832190256
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# plocate

> Find filenames quickly.
> Make sure to run `sudo updatedb` to include new files.
> More information: <https://plocate.sesse.net>.

- Look for patterns in the database (recomputed periodically):

`plocate {{pattern}}`

- Look for a file by its exact filename (a pattern containing no globbing characters is interpreted as `*pattern*`):

`plocate */{{filename}}`

