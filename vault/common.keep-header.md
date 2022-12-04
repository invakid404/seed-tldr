---
id: common.keep-header
title: Keep Header
desc: ''
updated: 1670142130953
created: 1670142130953
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# keep-header

> Keep first line untouched by a command, passing it directly to `stdout`.
> More information: <https://github.com/eBay/tsv-utils#keep-header>.

- Sort a file and keep the first line at the top:

`keep-header {{path/to/file}} -- sort`

- Output first line directly to `stdout`, passing the remainder of the file through the specified command:

`keep-header {{path/to/file}} -- {{command}}`

- Read from `stdin`, sorting all except the first line:

`cat {{path/to/file}} | keep-header -- {{command}}`

- Grep a file, keeping the first line regardless of the search pattern:

`keep-header {{path/to/file}} -- grep {{pattern}}`

