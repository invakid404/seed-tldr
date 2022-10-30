---
id: common.pg_isready
title: Pg_isready
desc: ''
updated: 1667128726030
created: 1667128726030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pg_isready

> Check the connection status of a PostgreSQL server.
> More information: <https://www.postgresql.org/docs/current/app-pg-isready.html>.

- Check connection:

`pg_isready`

- Check connection with a specific hostname and port:

`pg_isready --host={{hostname}} --port={{port}}`

- Check connection displaying a message only when the connection fails:

`pg_isready --quiet`

