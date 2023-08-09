---
id: linux.pridecat
title: Pridecat
desc: ''
updated: 1691562059175
created: 1691562059175
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pridecat

> Like cat but more colorful :).
> More information: <https://github.com/lunasorcery/pridecat>.

- Print the contents of a file in pride colors to `stdout`:

`pridecat {{path/to/file}}`

- Print contents of a file in trans colors:

`pridecat {{path/to/file}} --{{transgender|trans}}`

- Alternate between lesbian and bisexual pride flags:

`pridecat {{path/to/file}} --lesbian --bi`

- Print contents of a file with the background colors changed:

`pridecat {{path/to/file}} -b`

- List directory contents in pride flag colors:

`ls | pridecat --{{flag}}`

