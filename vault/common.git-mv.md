---
id: common.git-mv
title: Git Mv
desc: ''
updated: 1685038808030
created: 1685038808030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git mv

> Move or rename files and update the Git index.
> More information: <https://git-scm.com/docs/git-mv>.

- Move a file inside the repo and add the movement to the next commit:

`git mv {{path/to/file}} {{new/path/to/file}}`

- Rename a file or directory and add the renaming to the next commit:

`git mv {{path/to/file_or_directory}} {{path/to/destination}}`

- Overwrite the file or directory in the target path if it exists:

`git mv --force {{path/to/file_or_directory}} {{path/to/destination}}`

