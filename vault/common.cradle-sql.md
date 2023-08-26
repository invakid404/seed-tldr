---
id: common.cradle-sql
title: Cradle Sql
desc: ''
updated: 1693073888431
created: 1693073888431
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cradle sql

> Manage Cradle SQL databases.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#sql>.

- Rebuild the database schema:

`cradle sql build`

- Rebuild the database schema for a specific package:

`cradle sql build {{package}}`

- Empty the entire database:

`cradle sql flush`

- Empty the database tables for a specific package:

`cradle sql flush {{package}}`

- Populate the tables for all packages:

`cradle sql populate`

- Populate the tables for a specific package:

`cradle sql populate {{package}}`

