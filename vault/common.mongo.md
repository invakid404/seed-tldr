---
id: common.mongo
title: Mongo
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
# mongo

> The legacy MongoDB shell. See `mongosh` for the new shell.
> Note: all connection options can be replaced with one string: `mongodb://user@host:port/db_name?authSource=authdb_name`.
> More information: <https://docs.mongodb.com/manual/reference/program/mongo>.

- Connect to a local database on the default port (`mongodb://localhost:27017`):

`mongo`

- Connect to a database:

`mongo --host {{host}} --port {{port}} {{db_name}}`

- Authenticate using the specified username on the specified database (you will be prompted for a password):

`mongo --host {{host}} --port {{port}} --username {{username}} --authenticationDatabase {{authdb_name}} {{db_name}}`

- Evaluate a JavaScript expression on a database:

`mongo --eval '{{JSON.stringify(db.foo.findOne())}}' {{db_name}}`

