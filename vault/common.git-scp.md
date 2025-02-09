---
id: common.git-scp
title: Git Scp
desc: ''
updated: 1667397363559
created: 1667397363559
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git scp

> Copy files from the current working tree to the working directory of a remote repository.
> Part of `git-extras`. Uses `rsync` to transfer files.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-scp>.

- Copy unstaged files to a specific remote:

`git scp {{remote_name}}`

- Copy staged and unstaged files to a remote:

`git scp {{remote_name}} HEAD`

- Copy files that has been changed in the last commit and any staged or unstaged files to a remote:

`git scp {{remote_name}} HEAD~1`

- Copy specific files to a remote:

`git scp {{remote_name}} {{path/to/file1 path/to/file2 ...}}`

- Copy a specific directory to a remote:

`git scp {{remote_name}} {{path/to/directory}}`

