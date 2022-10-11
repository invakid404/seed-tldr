---
id: common.jhat
title: Jhat
desc: ''
updated: 1665463523018
created: 1665463523018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jhat

> Java heap analysis tool.
> More information: <https://docs.oracle.com/javase/8/docs/technotes/tools/unix/jhat.html>.

- Analyze a heap dump (from `jmap`), view via HTTP on port 7000:

`jhat {{dump_file.bin}}`

- Analyze a heap dump, specifying an alternate port for the http server:

`jhat -p {{port}} {{dump_file.bin}}`

- Analyze a dump letting `jhat` use up to 8 GB RAM (2-4x dump size recommended):

`jhat -J-mx8G {{dump_file.bin}}`

