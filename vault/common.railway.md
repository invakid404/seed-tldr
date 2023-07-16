---
id: common.railway
title: Railway
desc: ''
updated: 1689531679703
created: 1689531679703
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# railway

> Connect code to a Railway project.
> More information: <https://railway.app/>.

- Login to a Railway account:

`railway login`

- Link to an existing Project under a Railway account or team:

`railway link {{projectId}}`

- Create a new project:

`railway init`

- Run a local command using variables from the active environment:

`railway run {{cmd}}`

- Deploy the linked project directory (if running from a subdirectory, the project root is still deployed):

`railway up`

- Open an interactive shell to a database:

`railway connect`

