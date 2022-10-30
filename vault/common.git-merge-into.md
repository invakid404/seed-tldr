---
id: common.git-merge-into
title: Git Merge Into
desc: ''
updated: 1667172278959
created: 1667172278959
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git merge-into

> Merge one branch into another branch.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-merge-into>.

- Merge a source branch into a specific destination branch:

`git merge-into {{source_branch}} {{destination_branch}}`

- Merge current branch into a specific destination branch:

`git merge-into {{destination_branch}}`

