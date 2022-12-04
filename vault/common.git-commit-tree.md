---
id: common.git-commit-tree
title: Git Commit Tree
desc: ''
updated: 1670142130919
created: 1670142130919
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git commit-tree

> Low level utility to create commit objects.
> See also: `git commit`.
> More information: <https://git-scm.com/docs/git-commit-tree>.

- Create a commit object with the specified message:

`git commit-tree {{tree}} -m "{{message}}"`

- Create a commit object reading the message from a file (use `-` for `stdin`):

`git commit-tree {{tree}} -F {{path/to/file}}`

- Create a GPG-signed commit object:

`git commit-tree {{tree}} -m "{{message}}" --gpg-sign`

- Create a commit object with the specified parent commit object:

`git commit-tree {{tree}} -m "{{message}}" -p {{parent_commit_sha}}`

