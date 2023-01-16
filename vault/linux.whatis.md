---
id: linux.whatis
title: Whatis
desc: ''
updated: 1673893294256
created: 1673893294256
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# whatis

> Display one-line descriptions from manual pages.
> More information: <https://manned.org/whatis>.

- Display a description from a man page:

`whatis {{command}}`

- Don't cut the description off at the end of the line:

`whatis --long {{command}}`

- Display descriptions for all commands matching a glob:

`whatis --wildcard {{net*}}`

- Search man page descriptions with a regular expression:

`whatis --regex '{{wish[0-9]\.[0-9]}}'`

- Display descriptions of a specific language (requires `manpage-{{locale}}` package):

`whatis --locale={{en}} {{command}}`

