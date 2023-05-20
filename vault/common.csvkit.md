---
id: common.csvkit
title: Csvkit
desc: ''
updated: 1684545527721
created: 1684545527721
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvkit

> Manipulation toolkit for CSV files.
> See also: `csvclean`, `csvcut`, `csvformat`, `csvgrep`, `csvlook`, `csvpy`, `csvsort`, `csvstat`.
> More information: <https://csvkit.readthedocs.io/en/0.9.1/cli.html>.

- Run a command on a CSV file with a custom delimiter:

`{{command}} -d {{delimiter}} {{path/to/file.csv}}`

- Run a command on a CSV file with a tab as a delimiter (overrides -d):

`{{command}} -t {{path/to/file.csv}}`

- Run a command on a CSV file with a custom quote character:

`{{command}} -q {{quote_char}} {{path/to/file.csv}}`

- Run a command on a CSV file with no header row:

`{{command}} -H {{path/to/file.csv}}`

