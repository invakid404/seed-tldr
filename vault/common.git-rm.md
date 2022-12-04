---
id: common.git-rm
title: Git Rm
desc: ''
updated: 1670145406972
created: 1670145406972
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git rm

> Remove files from repository index and local filesystem.
> More information: <https://git-scm.com/docs/git-rm>.

- Remove file from repository index and filesystem:

`git rm {{path/to/file}}`

- Remove directory:

`git rm -r {{path/to/directory}}`

- Remove file from repository index but keep it untouched locally:

`git rm --cached {{path/to/file}}`

