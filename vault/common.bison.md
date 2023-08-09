---
id: common.bison
title: Bison
desc: ''
updated: 1691562058926
created: 1691562058926
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bison

> GNU parser generator.
> More information: <https://www.gnu.org/software/bison/>.

- Compile a bison definition file:

`bison {{path/to/file.y}}`

- Compile in debug mode, which causes the resulting parser to write additional information to `stdout`:

`bison --debug {{path/to/file.y}}`

- Specify the output filename:

`bison --output {{path/to/output.c}} {{path/to/file.y}}`

- Be verbose when compiling:

`bison --verbose`

