---
id: common.mysqlcheck
title: Mysqlcheck
desc: ''
updated: 1683599668605
created: 1683599668605
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mysqlcheck

> Check and repair MySQL tables.
> More information: <https://dev.mysql.com/doc/refman/8.0/en/mysqlcheck.html>.

- Check a table:

`mysqlcheck --check {{table}}`

- Check a table and provide credentials to access it:

`mysqlcheck --check {{table}} --user {{username}} --password {{password}}`

- Repair a table:

`mysqlcheck --repair {{table}}`

- Optimize a table:

`mysqlcheck --optimize {{table}}`

