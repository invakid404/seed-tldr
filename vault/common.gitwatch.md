---
id: common.gitwatch
title: Gitwatch
desc: ''
updated: 1685929377948
created: 1685929377948
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitwatch

> Automatically commit file or directory changes to a git repository.
> More information: <https://github.com/gitwatch/gitwatch>.

- Automatically commit any changes made to a file or directory:

`gitwatch {{path/to/file_or_directory}}`

- Automatically commit changes and push them to a remote repository:

`gitwatch -r {{remote_name}} {{path/to/file_or_directory}}`

- Automatically commit changes and push them to a specific branch of a remote repository:

`gitwatch -r {{remote_name}} -b {{branch_name}} {{path/to/file_or_directory}}`

