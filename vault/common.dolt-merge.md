---
id: common.dolt-merge
title: Dolt Merge
desc: ''
updated: 1665895276229
created: 1665895276229
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt merge

> Join two or more development histories together.
> More information: <https://github.com/dolthub/dolt>.

- Incorporate changes from the named commits into the current branch:

`dolt merge {{branch_name}}`

- Incorporate changes from the named commits into the current branch without updating the commit history:

`dolt merge --squash {{branch_name}}`

- Merge a branch and create a merge commit even when the merge resolves as a fast-forward:

`dolt merge --no-ff {{branch_name}}`

- Merge a branch and create a merge commit with a specific commit message:

`dolt merge --no-ff -m "{{message}}" {{branch_name}}`

- Abort the current conflict resolution process:

`dolt merge --abort`

