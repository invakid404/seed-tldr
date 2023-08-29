---
id: common.objdump
title: Objdump
desc: ''
updated: 1693293286957
created: 1693293286957
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

- Display all header information:

`objdump -x {{binary}}`

- Display the disassembled output of executable sections:

`objdump -d {{binary}}`

- Display the disassembled executable sections in intel syntax:

`objdump -M intel -d {{binary}}`

- Display a complete binary hex dump of all sections:

`objdump -s {{binary}}`

