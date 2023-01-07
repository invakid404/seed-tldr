---
id: common.git-credential-store
title: Git Credential Store
desc: ''
updated: 1673104608697
created: 1673104608697
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git credential-store

> `git` helper to store passwords on disk.
> More information: <https://git-scm.com/docs/git-credential-store>.

- Store Git credentials in a specific file:

`git config credential.helper 'store --file={{path/to/file}}'`

