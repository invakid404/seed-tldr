---
id: common.enca
title: Enca
desc: ''
updated: 1670310991768
created: 1670310991768
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# enca

> Detect and convert the encoding of text files.
> More information: <https://github.com/nijel/enca>.

- Detect file(s) encoding according to the system's locale:

`enca {{path/to/file1 path/to/file2 ...}}`

- Detect file(s) encoding specifying a language in the POSIX/C locale format (e.g. zh_CN, en_US):

`enca -L {{language}} {{path/to/file1 path/to/file2 ...}}`

- Convert file(s) to a specific encoding:

`enca -L {{language}} -x {{to_encoding}} {{path/to/file1 path/to/file2 ...}}`

- Create a copy of an existing file using a different encoding:

`enca -L {{language}} -x {{to_encoding}} < {{original_file}} > {{new_file}}`

