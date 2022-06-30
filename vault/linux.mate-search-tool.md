---
id: linux.mate-search-tool
title: Mate Search Tool
desc: ''
updated: 1656591837635
created: 1656591837635
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mate-search-tool

> Search files in MATE desktop environment.
> More information: <https://manned.org/mate-search-tool>.

- Search files containing a specific string in their name in a specific directory:

`mate-search-tool --named={{string}} --path={{path/to/directory}}`

- Search files without waiting a user confirmation:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}}`

- Search files with name matching a specific regular expression:

`mate-search-tool --start --regex={{string}} --path={{path/to/directory}}`

- Set a sorting order in search results:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}} --sortby={{name|folder|size|type|date}}`

- Set a descending sorting order:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}} --descending`

- Search files owned by a specific user/group:

`mate-search-tool --start --{{user|group}}={{value}} --path={{path/to/directory}}`

