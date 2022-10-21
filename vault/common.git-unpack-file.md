---
id: common.git-unpack-file
title: Git Unpack File
desc: ''
updated: 1666356784401
created: 1666356784401
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git unpack-file

> Create a temporary file with a blob's contents.
> More information: <https://git-scm.com/docs/git-unpack-file>.

- Create a file holding the contents of the blob specified by its ID then print the name of the temporary file:

`git unpack-file {{blob_id}}`

