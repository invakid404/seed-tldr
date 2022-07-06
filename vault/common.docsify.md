---
id: common.docsify
title: Docsify
desc: ''
updated: 1657125156789
created: 1657125156789
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docsify

> Initialize and serve markdown documentation.
> More information: <https://cli.docsifyjs.org>.

- Initialize a new documentation in the current directory:

`docsify init`

- Initialize a new documentation in the specified directory:

`docsify init {{path/to/directory}}`

- Serve local documentation on `localhost:3000` with live reload:

`docsify serve {{path/to/directory}}`

- Serve local documentation on `localhost` at the specified port:

`docsify serve --port {{80}} {{path/to/directory}}`

- Generate a sidebar markdown file in the specified directory:

`docsify generate {{path/to/directory}}`

