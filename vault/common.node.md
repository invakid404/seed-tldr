---
id: common.node
title: Node
desc: ''
updated: 1665974351858
created: 1665974351858
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# node

> Server-side JavaScript platform (Node.js).
> More information: <https://nodejs.org>.

- Run a JavaScript file:

`node {{path/to/file}}`

- Start a REPL (interactive shell):

`node`

- Execute the specified file restarting the process when an imported file is changed (requires Node.js version 18.11+):

`node --watch {{path/to/file}}`

- Evaluate JavaScript code by passing it as an argument:

`node -e "{{code}}"`

- Evaluate and print result, useful to see node's dependencies versions:

`node -p "{{process.versions}}"`

- Activate inspector, pausing execution until a debugger is connected once source code is fully parsed:

`node --no-lazy --inspect-brk {{path/to/file}}`

