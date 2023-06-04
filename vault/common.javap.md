---
id: common.javap
title: Javap
desc: ''
updated: 1685843802152
created: 1685843802152
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# javap

> Disassemble one or more class files and list them.
> More information: <https://docs.oracle.com/en/java/javase/20/docs/specs/man/javap.html>.

- Disassemble and list a `.class` file:

`javap {{path/to/file.class}}`

- Disassemble and list multiple `.class` files:

`javap {{path/to/file1.class path/to/file2.class ...}}`

- Disassemble and list a built-in class file:

`javap java.{{package}}.{{class}}`

- Display help:

`javap -help`

- Display version:

`javap -version`

