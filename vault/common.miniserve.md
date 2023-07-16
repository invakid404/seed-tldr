---
id: common.miniserve
title: Miniserve
desc: ''
updated: 1689531679653
created: 1689531679653
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# miniserve

> Simple HTTP file server.
> More information: <https://github.com/svenstaro/miniserve>.

- Serve a directory:

`miniserve {{path/to/directory}}`

- Serve a single file:

`miniserve {{path/to/file}}`

- Serve a directory using HTTP basic authentication:

`miniserve --auth {{username}}:{{password}} {{path/to/directory}}`

