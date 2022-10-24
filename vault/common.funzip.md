---
id: common.funzip
title: Funzip
desc: ''
updated: 1666650385256
created: 1666650385256
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# funzip

> Print the content of the first (non-directory) member in an archive without extraction.
> More information: <https://manned.org/funzip>.

- Print the content of the first member in a `.zip` archive:

`funzip {{path/to/archive.zip}}`

- Print the content in a `.gz` archive:

`funzip {{path/to/archive.gz}}`

- Decrypt a `.zip` or `.gz` archive and print the content:

`funzip -password {{password}} {{path/to/archive}}`

