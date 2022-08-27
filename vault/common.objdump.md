---
id: common.objdump
title: Objdump
desc: ''
updated: 1661609946685
created: 1661609946685
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# objdump

> View information about object files.
> More information: <https://manned.org/objdump>.

- Display the file header information:

`objdump -f {{binary}}`

- Display the disassembled output of executable sections:

`objdump -d {{binary}}`

- Display the disassembled executable sections in intel syntax:

`objdump -M intel -d {{binary}}`

- Display a complete binary hex dump of all sections:

`objdump -s {{binary}}`

