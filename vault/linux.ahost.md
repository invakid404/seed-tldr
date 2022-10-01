---
id: linux.ahost
title: Ahost
desc: ''
updated: 1664604165526
created: 1664604165526
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ahost

> DNS lookup utility to display the A or AAAA record linked with a hostname or IP address.
> More information: <https://manned.org/ahost>.

- Print an `A` or `AAAA` record associated with a hostname or IP address:

`ahost {{example.com}}`

- Display some extra debugging output:

`ahost -d {{example.com}}`

- Display the record with a specified type:

`ahost -t {{a|aaaa|u}} {{example.com}}`

