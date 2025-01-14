---
id: common.colordiff
title: Colordiff
desc: ''
updated: 1656591837435
created: 1656591837435
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# colordiff

> A tool to colorize diff output.
> The Perl script colordiff is a wrapper for `diff` and produces the same output but with pretty syntax highlighting. Color schemes can be customized.
> More information: <https://github.com/kimmel/colordiff>.

- Compare files:

`colordiff {{file1}} {{file2}}`

- Output in two columns:

`colordiff -y {{file1}} {{file2}}`

- Ignore case differences in file contents:

`colordiff -i {{file1}} {{file2}}`

- Report when two files are the same:

`colordiff -s {{file1}} {{file2}}`

- Ignore white spaces:

`colordiff -w {{file1}} {{file2}}`

