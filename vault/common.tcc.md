---
id: common.tcc
title: Tcc
desc: ''
updated: 1685473997362
created: 1685473997362
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcc

> A tiny C compiler that can run C source files as scripts and otherwise has command-line options similar to `gcc`.
> More information: <https://bellard.org/tcc/tcc-doc.html>.

- Compile and link 2 source files to generate an executable:

`tcc -o {{executable_name}} {{path/to/file1.c}} {{path/to/file2.c}}`

- Directly run an input file like a script and pass arguments to it:

`tcc -run {{path/to/source_file.c}} {{arguments}}`

- Interpret C source files with a shebang inside the file:

`#!/full/path/to/tcc -run`

