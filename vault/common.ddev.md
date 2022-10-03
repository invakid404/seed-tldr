---
id: common.ddev
title: Ddev
desc: ''
updated: 1664769727563
created: 1664769727563
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ddev

> Container based local development tool for PHP environments.
> More information: <https://ddev.readthedocs.io>.

- Start up a project:

`ddev start`

- Configure a project's type and docroot:

`ddev config`

- [f]ollow the log trail:

`ddev logs -f`

- Run composer within the container:

`ddev composer`

- Install a specific Node.js version:

`ddev nvm install {{version}}`

- Export a database:

`ddev export-db --file={{/tmp/db.sql.gz}}`

- Run a specific command within a container:

`ddev exec {{echo 1}}`

