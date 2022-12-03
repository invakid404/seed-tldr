---
id: common.git-blame
title: Git Blame
desc: ''
updated: 1670048500866
created: 1670048500866
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git blame

> Show commit hash and last author on each line of a file.
> More information: <https://git-scm.com/docs/git-blame>.

- Print file with author name and commit hash on each line:

`git blame {{path/to/file}}`

- Print file with author email and commit hash on each line:

`git blame -e {{path/to/file}}`

- Print file with author name and commit hash on each line at a specific commit:

`git blame {{commit}} {{path/to/file}}`

- Print file with author name and commit hash on each line before a specific commit:

`git blame {{commit}}~ {{path/to/file}}`

