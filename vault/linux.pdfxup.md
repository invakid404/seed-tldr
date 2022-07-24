---
id: linux.pdfxup
title: Pdfxup
desc: ''
updated: 1658628609721
created: 1658628609721
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pdfxup

> N-up PDF pages.
> N-upping means putting multiple pages onto one page by scaling and rotating them into a grid.
> More information: <https://ctan.org/pkg/pdfxup>.

- Create a 2-up PDF:

`pdfxup -o {{path/to/output.pdf}} {{path/to/input.pdf}}`

- Create a PDF with 3 columns and 2 lines per page:

`pdfxup -x {{3}} -y {{2}} -o {{path/to/output.pdf}} {{path/to/input.pdf}}`

- Create a PDF in booklet mode (2-up, and pages are sorted to form a book when folded):

`pdfxup -b -o {{path/to/output.pdf}} {{path/to/input.pdf}}`

