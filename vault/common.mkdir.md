---
id: common.mkdir
title: Mkdir
desc: ''
updated: 1670145407014
created: 1670145407014
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkdir

> Creates a directory.
> More information: <https://www.gnu.org/software/coreutils/mkdir>.

- Create a directory in current directory or given path:

`mkdir {{path/to/directory}}`

- Create multiple directories in the current directory:

`mkdir {{directory_1 directory_2 ...}}`

- Create directories recursively (useful for creating nested dirs):

`mkdir -p {{path/to/directory}}`

