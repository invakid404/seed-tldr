---
id: linux.just-js
title: Just JS
desc: ''
updated: 1664801544668
created: 1664801544668
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# just

> A V8 JavaScript runtime for Linux.
> More information: <https://github.com/just-js/just>.

- Start a REPL (interactive shell):

`just`

- Run a JavaScript file:

`just {{path/to/file.js}}`

- Evaluate JavaScript code by passing it as an argument:

`just eval "{{code}}"`

- Initialize a new project in a directory of the same name:

`just init {{project_name}}`

- Build a JavaScript application into an executable:

`just build {{path/to/file.js}} --static`

