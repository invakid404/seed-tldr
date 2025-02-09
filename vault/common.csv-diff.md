---
id: common.csv-diff
title: Csv Diff
desc: ''
updated: 1664245302487
created: 1664245302487
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csv-diff

> View differences between two CSV, TSV or JSON files.
> More information: <https://github.com/simonw/csv-diff>.

- Display a human-readable summary of differences between files using a specific column as a unique identifier:

`csv-diff {{path/to/file1.csv}} {{path/to/file2.csv}} --key={{column_name}}`

- Display a human-readable summary of differences between files that includes unchanged values in rows with at least one change:

`csv-diff {{path/to/file1.csv}} {{path/to/file2.csv}} --key={{column_name}} --show-unchanged`

- Display a summary of differences between files in JSON format using a specific column as a unique identifier:

`csv-diff {{path/to/file1.csv}} {{path/to/file2.csv}} --key={{column_name}} --json`

