---
id: linux.unzipsfx
title: Unzipsfx
desc: ''
updated: 1667133702864
created: 1667133702864
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unzipsfx

> Create a self-extracting compressed binary file by prepending self-extracting stubs on a `zip` file.
> More information: <https://manned.org/unzipsfx>.

- Create a self-extracting binary file of a `zip` archive:

`cat unzipsfx {{path/to/archive.zip}} > {{filename}} && chmod 755 {{filename}}`

- Extract a self-extracting binary in the current directory:

`{{./path/to/binary)}}`

- Test a self-extracting binary for errors:

`{{./path/to/binary)}} -t`

- Print content of a file in the self-extracting binary without extraction:

`{{./path/to/binary)}} -c {{path/to/filename}}`

- Print comments on `zip` archive in the self-extracting binary:

`{{./path/to/binary)}} -z`

