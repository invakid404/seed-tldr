---
id: linux.trashy
title: Trashy
desc: ''
updated: 1665294081904
created: 1665294081904
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trashy

> An alternative to `rm` and `trash-cli` written in Rust.
> More information: <https://github.com/oberblastmeister/trashy>.

- Move a specific file to the trash:

`trash {{path/to/file}}`

- Move specific files to the trash:

`trash {{path/to/file1 path/to/file2 ...}}`

- List items in the trash:

`trash list`

- Restore a specific file from the trash:

`trash restore {{file}}`

- Remove a specific file from the trash:

`trash empty {{file}}`

- Restore all files from the trash:

`trash restore --all`

- Remove all files from the trash:

`trash empty --all`

