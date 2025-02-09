---
id: common.okular
title: Okular
desc: ''
updated: 1670243723056
created: 1670243723056
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# okular

> View documents.
> More information: <https://docs.kde.org/stable5/en/okular/okular/command-line-options.html>.

- Launch document viewer:

`okular`

- Open specific documents:

`okular {{path/to/file1 path/to/file2 ...}}`

- Open a document at a specific page:

`okular --page {{page_number}} {{path/to/file}}`

- Open a specific document in presentation mode:

`okular --presentation {{path/to/file}}`

- Open a specific document and start a print dialog:

`okular --print {{path/to/file}}`

- Open a document and search for a specific string:

`okular --find {{search_string}} {{path/to/file}}`

