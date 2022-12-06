---
id: common.mongod
title: Mongod
desc: ''
updated: 1670310991827
created: 1670310991827
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mongod

> The MongoDB database server.
> More information: <https://docs.mongodb.com/manual/reference/program/mongod>.

- Specify a config file:

`mongod --config {{path/to/file}}`

- Specify the port to listen on:

`mongod --port {{port}}`

- Specify database profiling level. 0 is off, 1 is only slow operations, 2 is all:

`mongod --profile {{0|1|2}}`

