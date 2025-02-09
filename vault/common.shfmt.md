---
id: common.shfmt
title: Shfmt
desc: ''
updated: 1683303695887
created: 1683303695887
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shfmt

> Shell parser, formatter and interpreter.
> More information: <https://pkg.go.dev/mvdan.cc/sh>.

- Print a formatted version of a shell script:

`shfmt {{path/to/file}}`

- List unformatted files:

`shfmt --list {{path/to/directory}}`

- Write the result to the file instead of printing it to the terminal:

`shfmt --write {{path/to/file}}`

- Simplify the code, removing redundant pieces of syntax (i.e. removing "$" from vars in expressions):

`shfmt --simplify {{path/to/file}}`

