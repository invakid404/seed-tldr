---
id: common.pdftotext
title: Pdftotext
desc: ''
updated: 1691562059051
created: 1691562059051
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdftotext

> Convert PDF files to plain text format.
> More information: <https://www.xpdfreader.com/pdftotext-man.html>.

- Convert `filename.pdf` to plain text and print it to `stdout`:

`pdftotext {{filename.pdf}} -`

- Convert `filename.pdf` to plain text and save it as `filename.txt`:

`pdftotext {{filename.pdf}}`

- Convert `filename.pdf` to plain text and preserve the layout:

`pdftotext -layout {{filename.pdf}}`

- Convert `input.pdf` to plain text and save it as `output.txt`:

`pdftotext {{input.pdf}} {{output.txt}}`

- Convert pages 2, 3 and 4 of `input.pdf` to plain text and save them as `output.txt`:

`pdftotext -f {{2}} -l {{4}} {{input.pdf}} {{output.txt}}`

