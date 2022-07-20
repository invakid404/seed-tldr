---
id: common.duf
title: Duf
desc: ''
updated: 1658324747635
created: 1658324747635
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# duf

> Disk Usage/Free Utility.
> More information: <https://github.com/muesli/duf>.

- List accessible devices:

`duf`

- List everything (such as pseudo, duplicate or inaccessible file systems):

`duf --all`

- Only show specified devices or mount points:

`duf {{path/to/directory1 path/to/directory2 ...}}`

- Sort the output by a specified criteria:

`duf --sort {{size|used|avail|usage}}`

