---
id: common.dolt-sql
title: Dolt Sql
desc: ''
updated: 1665463522937
created: 1665463522937
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt sql

> Run a SQL query. Multiple SQL statements must be separated by semicolons.
> More information: <https://docs.dolthub.com/cli-reference/cli#dolt-sql>.

- Run a single query:

`dolt sql --query "{{INSERT INTO t values (1, 3);}}"`

- List all saved queries:

`dolt sql --list-saved`

