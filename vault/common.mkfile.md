---
id: common.mkfile
title: Mkfile
desc: ''
updated: 1670310991826
created: 1670310991826
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfile

> Create one or more empty files of any size.
> More information: <https://manned.org/mkfile>.

- Create an empty file of 15 kilobytes:

`mkfile -n {{15k}} {{path/to/file}}`

- Create a file of a given size and unit (bytes, KB, MB, GB):

`mkfile -n {{size}}{{b|k|m|g}} {{path/to/file}}`

- Create two files of 4 megabytes each:

`mkfile -n {{4m}} {{first_filename}} {{second_filename}}`

