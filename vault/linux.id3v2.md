---
id: linux.id3v2
title: Id3v2
desc: ''
updated: 1671765565257
created: 1671765565257
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# id3v2

> Manages id3v2 tags, converts and lists id3v1.
> More information: <https://manned.org/id3v2.1>.

- List all genres:

`id3v2 ‐‐list‐genres`

- List all tags of specific files:

`id3v2 --list-tags {{path/to/file1 path/to/file2 ...}}`

- Delete all `id3v2` or `id3v1` tags of specific files:

`id3v2 {{--delete‐v2|--delete‐v1}} {{path/to/file1 path/to/file2 ...}}`

- Display help:

`id3v2 --help`

- Display version:

`id3v2 ‐‐version`

