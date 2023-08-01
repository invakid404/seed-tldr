---
id: common.mongod
title: Mongod
desc: ''
updated: 1690878026474
created: 1690878026474
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

- Specify the storage directory (default: `/data/db` on Linux and MacOS, `C:\data\db` on Windows):

`mongod --dbpath {{path/to/directory}}`

- Specify a config file:

`mongod --config {{path/to/file}}`

- Specify the port to listen on (default: 27017):

`mongod --port {{port}}`

- Specify the database profiling level. 0 is off, 1 is only slow operations, 2 is all (default: 0):

`mongod --profile {{0|1|2}}`

