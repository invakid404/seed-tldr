---
id: common.git-merge-repo
title: Git Merge Repo
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
# git merge-repo

> Merge two repository histories.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-merge-repo>.

- Merge a repository's branch into the current repository's directory:

`git merge-repo {{path/to/repo}} {{branch_name}} {{path/to/directory}}`

- Merge a remote repository's branch into the current repository's directory, not preserving history:

`git merge-repo {{path/to/remote_repo}} {{branch_name}} .`

