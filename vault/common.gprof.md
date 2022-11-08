---
id: common.gprof
title: Gprof
desc: ''
updated: 1667946160932
created: 1667946160932
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gprof

> Performance analysis tool for many programming languages.
> It profiles the function executions of a program.
> More information: <https://ftp.gnu.org/old-gnu/Manuals/gprof-2.9.1/html_mono/gprof.html>.

- Compile binary with gprof information and run it to get `gmon.out`:

`gcc -pg {{program.c}} && {{./a.out}}`

- Run gprof to obtain profile output:

`gprof`

- Suppress profile field's description:

`gprof -b`

- Display routines that have zero usage:

`gprof -bz`

