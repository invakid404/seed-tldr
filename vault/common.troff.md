---
id: common.troff
title: Troff
desc: ''
updated: 1660961285183
created: 1660961285183
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# troff

> Typesetting processor for the groff (GNU Troff) document formatting system.
> See also `groff`.
> More information: <https://manned.org/troff>.

- Format output for a PostScript printer, saving the output to a file:

`troff {{path/to/input.roff}} | grops > {{path/to/output.ps}}`

- Format output for a PostScript printer using the [me] macro package, saving the output to a file:

`troff -{{me}} {{path/to/input.roff}} | grops > {{path/to/output.ps}}`

- Format output as [a]SCII text using the [man] macro package:

`troff -T {{ascii}} -{{man}} {{path/to/input.roff}} | grotty`

- Format output as a [pdf] file, saving the output to a file:

`troff -T {{pdf}} {{path/to/input.roff}} | gropdf > {{path/to/output.pdf}}`

