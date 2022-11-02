---
id: common.errno
title: Errno
desc: ''
updated: 1667406929928
created: 1667406929928
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# errno

> Look up errno names and descriptions.
> More information: <https://joeyh.name/code/moreutils/>.

- Lookup errno description by name or code:

`errno {{name|code}}`

- List all errno names, codes, and descriptions:

`errno --list`

- Search for code whose description contains all of the given text:

`errno --search {{text}}`

- Search for code whose description contains all of the given text (all locales):

`errno --search-all-locales {{text}}`

